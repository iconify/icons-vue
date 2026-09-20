<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcipywk0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-shipping-rounded" /></template>
<style>
.rcipywk0t {
  fill: currentColor;
  d: path("M3.837 18.356q-.76-.76-.76-1.856H2.5q-.348 0-.578-.23t-.23-.578V6.616q0-.691.463-1.153T3.308 5h11.615q.671 0 1.143.472q.473.472.473 1.143v2h1.5q.378 0 .726.175q.348.174.566.472l2.815 3.79q.081.106.121.227t.04.257v2.156q0 .348-.229.578q-.23.23-.578.23h-.808q0 1.096-.76 1.856q-.759.76-1.855.76t-1.856-.76t-.76-1.856H8.309q0 1.096-.76 1.856t-1.856.76t-1.856-.76m3.001-.71q.47-.471.47-1.146t-.47-1.145t-1.145-.47t-1.145.47t-.47 1.145t.47 1.145t1.145.47t1.146-.47m12.384 0q.47-.47.47-1.145t-.47-1.145t-1.145-.47t-1.145.47t-.47 1.145t.47 1.145t1.145.47t1.145-.47M16.538 13.5h4.712L18.5 9.866q-.096-.116-.221-.183T18 9.616h-1.461z");
}

</style>
