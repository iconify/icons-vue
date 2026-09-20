<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ak8laogjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crop-7-5-sharp" /></template>
<style>
.ak8laogjk {
  fill: currentColor;
  d: path("M3 19V5h18v14z");
}

</style>
