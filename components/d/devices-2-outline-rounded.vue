<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwz5-rbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:devices-2-outline-rounded" /></template>
<style>
.kwz5-rbtj {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.731q.213 0 .357.144t.143.357t-.143.356t-.357.143H4.616q-.27 0-.443.173T4 6.616v10.769q0 .23.192.423t.424.192h6.923q.212 0 .356.144t.144.357t-.144.356t-.356.143zm15.576-1.327v-7.577q0-.134-.096-.23q-.096-.097-.23-.097h-3.732q-.134 0-.23.096t-.096.231v7.577q0 .135.096.23q.096.097.23.097h3.731q.135 0 .231-.096t.096-.231M16.02 19q-.504 0-.858-.353q-.353-.354-.353-.858V9.98q0-.505.353-.858q.353-.354.858-.354h3.962q.504 0 .858.353q.353.354.353.859v7.807q0 .505-.353.859q-.353.353-.858.353zm1.978-6.5q.29 0 .483-.2q.193-.202.193-.47q0-.29-.193-.483t-.488-.193q-.273 0-.469.193t-.196.488q0 .273.2.469q.201.196.47.196M18 13.885");
}

</style>
