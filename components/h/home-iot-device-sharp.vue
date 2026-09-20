<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqip2j0ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:home-iot-device-sharp" /></template>
<style>
.dqip2j0ag {
  fill: currentColor;
  d: path("M5.698 10.308h1.616v-3.5q0-.34-.224-.574T6.506 6q-.322 0-.565.234q-.243.233-.243.574zM6.506 19q-1.49 0-2.534-1.04t-1.043-2.537q0-1.008.483-1.814q.482-.805 1.286-1.27V6.807q0-.762.533-1.285T6.506 5q.78 0 1.294.523t.514 1.285v5.53q.784.466 1.277 1.281t.492 1.823q0 1.471-1.053 2.515Q7.977 19 6.506 19m6.598-4.192q-1.065-.69-1.815-1.827t-.75-2.712q0-2.192 1.538-3.73T15.807 5t3.731 1.539t1.539 3.73q0 1.575-.75 2.712t-1.816 1.827zm1.788 3.8q-.392-.392-.392-.916h2.616q0 .524-.393.916q-.392.392-.915.392q-.524 0-.916-.392m-1.508-1.8v-1h4.847v1z");
}

</style>
