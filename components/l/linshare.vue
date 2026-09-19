<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qh_mmdbxi"/><path class="qqn992oow"/><path class="wnwb56mjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:linshare" /></template>
<style>
.qh_mmdbxi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.158 18.358c2.362-11.687 16.079-8.825 17.166-.974c3.678.451 5.166 2.448 5.812 5.04c10.282 1.09 9.129 14.973.672 15.05H12.52c-10.296-.205-11.302-16.771.638-19.116");
}

.qqn992oow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.363 30.015l-1.58 1.68a2.487 2.487 0 0 1-3.392-3.628l2.419-2.587a2.444 2.444 0 0 1 3.729.37");
}

.wnwb56mjp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.389 27.294a2.355 2.355 0 0 0 3.796-.1l2.351-2.453c1.978-2.634-1.665-5.326-3.426-3.292l-1.445 1.444");
}

</style>
