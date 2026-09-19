<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gdgy4bclg"/><path class="le6fvhbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dramabox" /></template>
<style>
.gdgy4bclg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.612 23.748c0 3.628.092 6.67.222 9.153c.251 4.824 4.251 8.594 9.081 8.594h7.548c9.801 0 17.747-7.946 17.747-17.747h0C41.21 13.946 33.264 6 23.463 6h-7.548c-4.83 0-8.83 3.77-9.081 8.594c-.13 2.483-.222 5.526-.222 9.154");
}

.le6fvhbcj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.455 25.862l-10.866 6.274c-1.23.71-2.795.03-3.107-1.355c-.362-1.61-.706-3.95-.706-7.033s.344-5.424.706-7.033a2.102 2.102 0 0 1 3.106-1.355l10.866 6.273c1.628.94 1.628 3.29 0 4.23");
}

</style>
