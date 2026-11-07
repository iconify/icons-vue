<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqoqxlr9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:devices-2-rounded" /></template>
<style>
.hqoqxlr9d {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h15.116q.517 0 .912.28t.55.72h-5.558q-1.527 0-2.562 1.035t-1.035 2.561v7.789q0 .666-.474 1.14T10.423 19zm11.403 0q-.504 0-.858-.353q-.353-.354-.353-.858V9.98q0-.51.353-.86q.353-.352.858-.352h3.958q.514 0 .864.351q.351.351.351.86v7.808q0 .505-.35.859q-.351.353-.865.353zm1.978-6.5q.29 0 .483-.2q.193-.202.193-.47q0-.29-.193-.483t-.488-.193q-.273 0-.469.193t-.196.488q0 .273.2.469q.201.196.47.196");
}

</style>
