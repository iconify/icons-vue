<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="bmlp1dldp"/><path class="j4oyjgb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:heart-decoration" /></template>
<style>
.bmlp1dldp {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.j4oyjgb9n {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M31.885 13.764a7.66 7.66 0 0 0-7.66-7.661A7.65 7.65 0 0 0 18 9.309a7.65 7.65 0 0 0-6.224-3.206a7.66 7.66 0 0 0-7.661 7.661c0 .6.076 1.18.206 1.74C5.385 22.113 12.733 29.085 18 31c5.266-1.915 12.614-8.887 13.678-15.496c.131-.56.207-1.14.207-1.74");
}

</style>
