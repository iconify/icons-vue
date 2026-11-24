<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oe83hbvja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circus-tent-fill-sharp" /></template>
<style>
.oe83hbvja {
  fill: currentColor;
  d: path("M11 6.538V3a1.002 1.002 0 0 1 1.316-.949l3 1a1 1 0 0 1 0 1.898L13 5.721v.817c.381.273.816.469 1.25.639q.554.213 1.121.384c.875.269 1.764.492 2.637.772c.858.276 1.839.632 2.458 1.316l-.913.457A1 1 0 0 0 19 11v.013A1 1 0 0 1 17 11a1 1 0 0 0-2 0a.997.997 0 0 1-1 1a.997.997 0 0 1-1-1a1 1 0 0 0-2 0a.997.997 0 0 1-1 1a.997.997 0 0 1-1-1a1 1 0 0 0-2 0a1 1 0 0 1-2 .013V11a1 1 0 0 0-.553-.894l-.913-.457c.619-.684 1.6-1.04 2.458-1.316c.873-.28 1.762-.503 2.637-.772q.567-.171 1.121-.384c.434-.17.869-.366 1.25-.639M7.293 20.293A1 1 0 0 0 7 21v1H4a1 1 0 0 1-1-1v-9.382l.071.036A3 3 0 0 0 8 13.236a3 3 0 0 0 4 0a3 3 0 0 0 4 0a3 3 0 0 0 4.929-1.582l.071-.036V21a1 1 0 0 1-1 1h-3v-1a1 1 0 0 0-.293-.707l-4-4a1 1 0 0 0-1.414 0ZM9 21.414l3-3l3 3V22H9Z");
}

</style>
