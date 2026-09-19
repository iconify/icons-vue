<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="cf6kmbb0v"/><path class="ahv46fxbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-indonesia" /></template>
<style>
.ahv46fxbf {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M0 21c0-6.075 3.373-11 10-11h44c6.627 0 10 4.925 10 11v11H0z");
}

.cf6kmbb0v {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M54 54H10C3.373 54 0 49.075 0 43V32h64v11c0 6.075-3.373 11-10 11");
}

</style>
