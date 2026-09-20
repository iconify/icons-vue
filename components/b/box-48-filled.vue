<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b3xeb2byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:box-48-filled" /></template>
<style>
.b3xeb2byh {
  fill: currentColor;
  d: path("M26.321 4.832a6.25 6.25 0 0 0-4.642 0l-5.29 2.116l18.738 7.505l7.344-2.938a4.3 4.3 0 0 0-1.143-.68zm5.442 10.967L13.024 8.294l-6.352 2.54c-.422.17-.806.4-1.143.681L24 18.904zM4 14.78c0-.386.052-.764.151-1.124l18.599 7.44v22.391a6 6 0 0 1-1.071-.32L6.672 37.163A4.25 4.25 0 0 1 4 33.219zm22.321 28.386q-.524.21-1.071.321V21.096l18.599-7.44c.099.361.151.739.151 1.125v18.438a4.25 4.25 0 0 1-2.672 3.945z");
}

</style>
