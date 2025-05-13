<template>
  <main>
    <div class="container mt-5">
      <div class="card">
        <div class="card-header">
          <h4>
            Drivers
            <RouterLink to="/drivers/create" class="btn btn-primary float-end"
              >Add Drivers</RouterLink
            >
          </h4>
        </div>
        <div class="card-body">
          <table class="table table-bordered">
            <thead>
              <tr>
                <th scope="col">ID</th>
                <th scope="col">Name</th>
                <th scope="col">Phone No</th>
                <th scope="col">Email</th>
              </tr>
            </thead>
          </table>
        </div>
      </div>
    </div>
  </main>
</template>
