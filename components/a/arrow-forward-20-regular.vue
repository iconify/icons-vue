<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dhg_bzmgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-forward-20-regular" /></template>
<style>
.dhg_bzmgt {
  fill: currentColor;
  d: path("M12.646 3.646a.5.5 0 0 0 0 .708L16.293 8H9.5A7.5 7.5 0 0 0 2 15.5a.5.5 0 0 0 1 0A6.5 6.5 0 0 1 9.5 9h6.793l-3.647 3.646a.5.5 0 0 0 .708.708l4.5-4.5a.5.5 0 0 0 0-.708l-4.5-4.5a.5.5 0 0 0-.708 0");
}

</style>
