<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ebwdohu1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:code-text-off-16-regular" /></template>
<style>
.ebwdohu1d {
  fill: currentColor;
  d: path("m6.122 4l-1-1H7a.5.5 0 0 1 0 1zM9.5 4h5a.5.5 0 0 0 0-1h-5a.5.5 0 0 0 0 1m.5 2a.5.5 0 0 0 0 1h3.5a.5.5 0 0 0 0-1zm-1 6H1.5a.5.5 0 0 0 0 1H9a.5.5 0 0 0 0-1m5.854 2.145l-13-12.999a.5.5 0 0 0-.708.707L2.292 3H1.5a.5.5 0 0 0 0 1h1.792l2 2H4.5a.5.5 0 0 0 0 1h1.792l2 2H3.5a.5.5 0 0 0 0 1h5.792l4.854 4.854a.5.5 0 0 0 .708 0a.5.5 0 0 0 0-.708");
}

</style>
