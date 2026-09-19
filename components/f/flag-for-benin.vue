<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="a-54mdb9i"/><path class="zwq1gquwf"/><path class="apm0bwb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-benin" /></template>
<style>
.a-54mdb9i {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M0 43c0 6.075 3.373 11 10 11h44c6.627 0 10-4.925 10-11V32H0z");
}

.apm0bwb7m {
  fill: var(--svg-color--00785e, #00785e);
  d: path("M10 10C3.373 10 0 14.925 0 21v22c0 6.075 3.373 11 10 11h12V10z");
}

.zwq1gquwf {
  fill: var(--svg-color--f9cb38, #f9cb38);
  d: path("M54 10H10C3.373 10 0 14.925 0 21v12h64V21c0-6.075-3.373-11-10-11");
}

</style>
