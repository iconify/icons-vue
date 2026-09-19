<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="brjmdrbri"/><path class="x0kosdqld"/><path class="cjt-c7bzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-greenland" /></template>
<style>
.brjmdrbri {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M54 54H10C3.373 54 0 49.075 0 43V32h64v11c0 6.075-3.373 11-10 11");
}

.cjt-c7bzb {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M18.18 19.284C11.16 19.284 5.464 25 5.464 32h25.432c0-7-5.694-12.716-12.716-12.716");
}

.x0kosdqld {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M0 21c0-6.075 3.373-11 10-11h44c6.627 0 10 4.925 10 11v11H0zm18.18 23.715C25.2 44.715 30.896 40 30.896 32H5.464c0 8 5.693 12.715 12.716 12.715");
}

</style>
