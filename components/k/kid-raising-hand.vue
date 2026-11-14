<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nc8ucplyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:kid-raising-hand" /></template>
<style>
.nc8ucplyh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 7q0-1.968 1.391-3.359T10.5 2.25t3.359 1.391T15.25 7t-1.391 3.359T10.5 11.75t-3.359-1.391T5.75 7m11.334 8.737l2.645-11.063q.035-.145.012-.292t-.102-.274q-.078-.128-.199-.215q-.12-.088-.266-.122q-.071-.018-.145-.02t-.147.008q-.073.012-.142.038t-.132.064t-.118.089t-.097.11q-.044.06-.074.127q-.031.067-.048.139L15.8 14.658q-2.066-1.408-5.3-1.408q-3.462 0-5.782 1.673Q2.25 16.702 2.25 19.5v1q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h15q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-3.134-1.666-4.763m-1.3.851q1.257 1.007 1.436 3.162H3.75v-.25q0-2.03 1.845-3.36q1.927-1.39 4.905-1.39q3.439 0 5.22 1.78q.029.03.061.056z");
}

</style>
