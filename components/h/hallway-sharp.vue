<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ey_mz0bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hallway-sharp" /></template>
<style>
.ey_mz0bhf {
  fill: currentColor;
  d: path("M4 21V5h4.885L12 1.885L15.116 5H20v16zm3.5-3.5h9.154l-2.827-3.77l-2.615 3.308l-1.75-2.115zM10.139 5h3.723L12 3.139z");
}

</style>
