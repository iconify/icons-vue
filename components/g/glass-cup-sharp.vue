<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dye3ux85q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:glass-cup-sharp" /></template>
<style>
.dye3ux85q {
  fill: currentColor;
  d: path("M6.027 21L4 3h16l-2.008 18zm.51-4.5h10.952L18.866 4H5.116z");
}

</style>
