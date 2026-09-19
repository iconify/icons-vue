<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zkm4ypklb"/><path class="kb1ekebkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:comaps" /></template>
<style>
.kb1ekebkr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.472 24.573L31.14 13.868c.58-.458 1.664.359 1.445.908L26.992 33.91c-.157.471-1.511.446-1.786-.001l-2.852-6.83l-7.251-1.028c-.572-.108-.826-1.085-.63-1.478");
}

.zkm4ypklb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.474 42.185A21.4 21.4 0 0 1 24 45.5C12.126 45.5 2.5 35.874 2.5 24S12.126 2.5 24 2.5c3.83 0 7.426 1.001 10.54 2.757m5 3.883A21.43 21.43 0 0 1 45.5 24a21.42 21.42 0 0 1-5.222 14.046");
}

</style>
