<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jdv11qxtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:life-supermarket" /></template>
<style>
.jdv11qxtw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.587 26.679a4.765 4.765 0 1 1-4.4-8.452a4.765 4.765 0 1 1 8.452-4.4c1.294 2.486 3.017 6.244 5.29 8.724c-3.284.728-6.856 2.834-9.342 4.128m20.826-7.601a4.765 4.765 0 1 1 4.4 8.452a4.765 4.765 0 1 1-8.452 4.4c-1.295-2.486-3.017-6.244-5.29-8.724c3.284-.728 6.856-2.834 9.342-4.128m-14.214-6.612a4.765 4.765 0 1 1 8.452-4.4a4.765 4.765 0 1 1 4.4 8.452c-2.486 1.294-6.244 3.017-8.724 5.29c-.728-3.284-2.834-6.856-4.128-9.342m7.602 20.826a4.765 4.765 0 1 1-8.452 4.4a4.765 4.765 0 1 1-4.4-8.452c2.486-1.295 6.244-3.017 8.724-5.29c.728 3.284 2.834 6.856 4.128 9.342m3.798 3.878c1.75 3.47 4.405 4.926 7.536 5.327");
}

</style>
