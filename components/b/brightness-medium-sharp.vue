<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzgbclbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:brightness-medium-sharp" /></template>
<style>
.xzgbclbgw {
  fill: currentColor;
  d: path("M12 21.916L9.069 19H5v-4.069L2.085 12L5 9.069V5h4.069L12 2.085L14.931 5H19v4.069L21.916 12L19 14.931V19h-4.069zm0-5.685q1.748 0 2.99-1.242q1.24-1.241 1.24-2.989t-1.237-2.99Q13.756 7.77 12 7.77z");
}

</style>
