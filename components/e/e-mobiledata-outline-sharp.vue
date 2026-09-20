<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxbclqw6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:e-mobiledata-outline-sharp" /></template>
<style>
.vxbclqw6i {
  fill: currentColor;
  d: path("M8.5 17V7h7v1h-6v3.5h6v1h-6V16h6v1z");
}

</style>
