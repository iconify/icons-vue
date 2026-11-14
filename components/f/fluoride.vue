<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr-571gis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fluoride" /></template>
<style>
.rr-571gis {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 1.75q.825 0 1.852.476q.591.274.898.274t.898-.274q1.027-.476 1.852-.476q4.25 0 4.25 5.25q0 1.781-1.101 4.69q-.501 1.324-.665 1.967l-.58 3.288q-.384.92-.403 1.722q-.463.958-1.626.958q-1.562 0-1.861-1.728l-.742-3.215l-.022-.182l-.019.169l-.745 3.228q-.299 1.728-1.861 1.728q-1.573 0-1.864-1.745l-.745-4.223q-.164-.643-.665-1.967Q1.75 8.781 1.75 7q0-5.25 4.25-5.25m12.78 11.47q3.47 3.469 3.47 5.53q0 1.657-1.172 2.828q-1.171 1.172-2.828 1.172q-4 0-4-4q0-2.061 3.47-5.53q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094m-3.03 5.53q0-1.307 2.5-3.927q2.5 2.62 2.5 3.927q0 1.036-.732 1.768t-1.768.732q-2.5 0-2.5-2.5");
}

</style>
