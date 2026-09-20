<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-w0hbcvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:checkroom-outline-sharp" /></template>
<style>
.j-w0hbcvf {
  fill: currentColor;
  d: path("M3 20q-.425 0-.712-.288T2 19q0-.25.1-.462t.3-.338l8.6-6.45V10q0-.425.3-.712T12.025 9q.625 0 1.05-.45t.425-1.075t-.437-1.05T12 6t-1.062.438T10.5 7.5h-2q0-1.45 1.025-2.475T12 4t2.475 1.013T15.5 7.475q0 1.175-.687 2.1T13 10.85v.9l8.6 6.45q.2.125.3.338T22 19q0 .425-.287.713T21 20zm3-2h12l-6-4.5z");
}

</style>
