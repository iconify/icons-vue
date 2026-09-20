<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nw1s_fb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:inprivate-account-16-filled" /></template>
<style>
.nw1s_fb6l {
  fill: currentColor;
  d: path("M11.5 8A1.5 1.5 0 0 1 13 9.5H8v1h4.96c-.053.34-.161.678-.32 1H8v1h3.929C11.073 13.383 9.731 14 8 14c-3.14 0-5-2.029-5-4v-.5A1.5 1.5 0 0 1 4.5 8zm-.795-4.25a2.8 2.8 0 0 1 0 1H8v1h2.305a2.75 2.75 0 1 1 0-3H8v1z");
}

</style>
