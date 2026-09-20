<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvyu1x31d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:language-us-colemak-sharp" /></template>
<style>
.tvyu1x31d {
  fill: currentColor;
  d: path("M14.5 15H18V9h-3.5zM4 17V7h6.5v2H6v6h4.5v2zm8.5 0V7H20v10z");
}

</style>
