<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="a1xej0buf"/><path class="a-54mdb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-poland" /></template>
<style>
.a-54mdb9i {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M0 43c0 6.075 3.373 11 10 11h44c6.627 0 10-4.925 10-11V32H0z");
}

.a1xej0buf {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M54 10H10C3.373 10 0 14.925 0 21v11h64V21c0-6.075-3.373-11-10-11");
}

</style>
