<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etcgpn3va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:call-quality-outline-sharp" /></template>
<style>
.etcgpn3va {
  fill: currentColor;
  d: path("M18.2 21q-2.702 0-5.418-1.244t-4.995-3.533t-3.533-5.021Q3 8.469 3 5.8V5h4.439l.848 4.083l-2.697 2.51q.685 1.186 1.418 2.167t1.527 1.769q.802.84 1.808 1.57t2.296 1.44l2.611-2.708l3.75.756V21zM5.121 10.654l2.092-1.92L6.635 6h-2.63q.03 1.144.309 2.305q.278 1.16.807 2.349m8.45 8.335q.923.463 2.09.723t2.339.277v-2.605l-2.388-.475zm-.253-8.304Q12 9.369 12 7.503t1.316-3.185T16.497 3q1.867 0 3.185 1.316Q21 5.63 21 7.497t-1.315 3.185T16.503 12t-3.185-1.315m2.798-.3h.769V6.807h-.77zM16 5.692h1v-1h-1z");
}

</style>
