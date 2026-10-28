<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi63olg7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:input-search-outline-sharp" /></template>
<style>
.hi63olg7e {
  fill: currentColor;
  d: path("M5 18h14zm-1 1v-8.5h5.48v1H5V18h14v-3.27h1V19zm10.361-9.442q1.17 0 1.981-.808t.812-1.977t-.808-1.971T14.37 4t-1.981.804t-.812 1.967t.808 1.975t1.976.812m.004 1q-1.578 0-2.683-1.105t-1.105-2.684q0-1.586 1.105-2.678T14.366 3t2.683 1.091q1.105 1.092 1.105 2.678q0 .648-.197 1.236q-.198.587-.56 1.074l3.188 3.202l-.708.727l-3.189-3.221q-.502.37-1.087.57t-1.236.2");
}

</style>
