<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq3hzfqpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:app-spark" /></template>
<style>
.uq3hzfqpl {
  fill: currentColor;
  d: path("M17.98 10.116q-.15 0-.2-.15q-.36-1.391-1.358-2.388q-.997-.997-2.387-1.359q-.15-.05-.15-.2q0-.175.15-.2q1.39-.361 2.387-1.358t1.359-2.388q.05-.15.2-.15q.169 0 .2.15q.361 1.39 1.358 2.387t2.388 1.36q.15.024.15.2q0 .15-.15.2q-1.39.36-2.387 1.358q-.998.997-1.36 2.388q-.024.15-.2.15M16.674 20H7.308q-1.381 0-2.344-.963T4 16.692V7.327q0-1.38.964-2.354Q5.927 4 7.307 4h4.827q-.423 1.652.016 3.298q.44 1.646 1.672 2.879q1.233 1.233 2.879 1.672q1.646.44 3.298.017v4.826q0 1.381-.973 2.345q-.973.963-2.354.963");
}

</style>
