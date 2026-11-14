<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuafhv6zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:astronaut-tether" /></template>
<style>
.tuafhv6zw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 9.5V15q0 .126.041.244q.041.119.118.218q-.159.439-.159 1.038v.5q0 2.25 2.25 2.25h11q2.25 0 2.25-2.25v-.5q0-.599-.159-1.038q.077-.099.118-.218q.041-.118.041-.244v-2.718q3.5.315 3.5 3.718q0 4.75-4.75 4.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q2.49 0 4.286-1.633Q22.25 18.832 22.25 16q0-2.238-1.615-3.737q-1.378-1.28-3.385-1.477V9.5q0-3.21-2.27-5.48T9.5 1.75T4.02 4.02T1.75 9.5m14 4.826q-.337-.076-.75-.076H4q-.413 0-.75.076V9.5q0-2.589 1.831-4.419Q6.911 3.25 9.5 3.25t4.419 1.831T15.75 9.5zM5.25 9.5q0-1.76 1.245-3.005T9.5 5.25t3.005 1.245T13.75 9.5t-1.245 3.005T9.5 13.75t-3.005-1.245T5.25 9.5");
}

</style>
