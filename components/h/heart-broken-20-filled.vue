<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i5empgavr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:heart-broken-20-filled" /></template>
<style>
.i5empgavr {
  fill: currentColor;
  d: path("M9.274 4.178a4.3 4.3 0 0 0-6.013.096c-1.688 1.705-1.68 4.476.016 6.189l6.277 6.34c.26.263.682.263.942 0l6.245-6.304a4.41 4.41 0 0 0-.017-6.187a4.305 4.305 0 0 0-6.135-.015l-.585.592l-1.344 2.06l2.996 2.53a.5.5 0 0 1 .031.735l-2 2a.5.5 0 1 1-.707-.707l1.615-1.616L7.678 7.43a.5.5 0 0 1-.097-.655z");
}

</style>
