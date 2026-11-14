<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iktpf5b5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:espresso-macchiato" /></template>
<style>
.iktpf5b5c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.208 9.25h4.656q.014-.665-.437-1.238q-.63-.801-1.648-.763q-.052.002-.103-.003q-1.11-.109-1.869.708q-.536.578-.599 1.296m6.162 0h2.13q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v.25h.25q3.25 0 3.25 3.25t-3.25 3.25h-.933q-.389.704-1.001 1.316q-1.684 1.684-4.066 1.684H10q-2.382 0-4.066-1.684T4.25 14v-4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T5 9.25h1.7q.056-1.291 1.008-2.316q1.248-1.344 3.065-1.185q1.747-.046 2.834 1.337q.787 1.002.763 2.164m2.754 6h.376q1.75 0 1.75-1.75t-1.75-1.75h-.25V14q0 .651-.126 1.25");
}

</style>
