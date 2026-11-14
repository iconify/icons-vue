<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="khlh8z1vy"/><path class="pc-wcccjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:helium-tank" /></template>
<style>
.khlh8z1vy {
  d: path("M13 14.123V21.5H4V10q0-.11.005-.221q.006-.11.017-.22q.01-.11.027-.219q.016-.11.037-.218q.022-.108.049-.215q.027-.108.059-.213q.032-.106.069-.21t.08-.206q.042-.102.089-.202t.099-.197t.109-.192t.118-.187q.062-.092.128-.181q.065-.088.135-.174t.145-.167q.074-.082.152-.16t.16-.152t.167-.145q.086-.07.174-.135q.089-.066.181-.128q.092-.061.187-.118q.094-.057.192-.109q.097-.052.197-.099t.202-.089t.206-.08t.21-.069t.213-.059t.215-.049t.218-.037q.109-.017.219-.027q.11-.011.22-.017Q8.39 5.5 8.5 5.5t.221.005q.11.006.22.017q.11.01.219.027q.11.016.218.037q.108.022.215.049q.108.027.213.059q.106.032.21.069t.206.08q.102.042.202.089t.197.099t.192.109t.187.118q.092.062.181.128q.088.065.174.135t.167.145q.082.074.16.152t.152.16t.145.167q.07.086.135.174q.066.089.128.181q.061.092.118.187q.057.094.109.192q.052.097.099.197t.089.202t.08.206t.069.21q.032.105.059.213q.027.107.049.215q.021.108.037.218q.017.109.027.219q.011.11.017.22Q13 9.89 13 10v3.923M8.5 2.5v3m-2-3h4M15.75 14a2.75 3.5 0 1 0 5.5 0a2.75 3.5 0 1 0-5.5 0Z");
}

.pc-wcccjq {
  d: path("M18.5 17.5q-1 2 0 4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
