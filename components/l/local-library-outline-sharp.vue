<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad8vghbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-library-outline-sharp" /></template>
<style>
.ad8vghbgl {
  fill: currentColor;
  d: path("M12 21.116q-1.684-1.374-3.721-2.168T4 18V8.654q2.294.135 4.36 1.095q2.065.96 3.64 2.378q1.575-1.418 3.64-2.378T20 8.654V18q-2.248.154-4.282.948T12 21.116m0-1.254q1.575-1.156 3.35-1.866t3.65-.934V9.776q-1.96.325-3.741 1.264T12 13.458q-1.477-1.477-3.259-2.417T5 9.777v7.285q1.875.225 3.65.934T12 19.862M9.714 7.632q-.945-.943-.945-2.286t.944-2.286T12 2.116t2.286.944t.945 2.286t-.944 2.287T12 8.577t-2.286-.944m3.862-.711q.655-.655.655-1.576t-.655-1.576T12 3.116t-1.576.654t-.655 1.576t.655 1.576q.655.655 1.576.655t1.576-.655M12 13.458");
}

</style>
