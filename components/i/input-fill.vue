<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qq1a4bbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:input-fill" /></template>
<style>
.qq1a4bbnn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1 9C1 7.3431 2.3431 6 4 6L20 6C21.6569 6 23 7.3431 23 9L23 15C23 16.6569 21.6569 18 20 18L4 18C2.3431 18 1 16.6569 1 15L1 9ZM7 11C7 10.4477 6.5523 10 6 10C5.4477 10 5 10.4477 5 11L5 13C5 13.5523 5.4477 14 6 14C6.5523 14 7 13.5523 7 13L7 11Z");
}

</style>
