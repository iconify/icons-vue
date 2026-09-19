<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ik8-3_bxu"/><path class="ylez0ismu"/><path class="mh7jcc21q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-denmark" /></template>
<style>
.ik8-3_bxu {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M64 43c0 6.075-3.373 11-10 11H10C3.373 54 0 49.075 0 43V21c0-6.075 3.373-11 10-11h44c6.627 0 10 4.925 10 11z");
}

.mh7jcc21q {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M0 27h64v8H0z");
}

.ylez0ismu {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M20 10h9v44h-9z");
}

</style>
