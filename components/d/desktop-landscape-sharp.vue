<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gionrr78c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:desktop-landscape-sharp" /></template>
<style>
.gionrr78c {
  fill: currentColor;
  d: path("M6 16h9v-5H6zm10.5-3H18V8H9v1.5h7.5zM2 20V4h20v16z");
}

</style>
