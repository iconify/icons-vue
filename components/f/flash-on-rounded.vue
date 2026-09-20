<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb91p8bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flash-on-rounded" /></template>
<style>
.nb91p8bln {
  fill: currentColor;
  d: path("M10.15 20.063Q10 19.875 10 19.6V14H9q-.825 0-1.412-.587T7 12V4q0-.825.588-1.412T9 2h5.85q.8 0 1.288.625T16.425 4L15 9h1.125q.9 0 1.338.8t-.088 1.55l-6 8.675q-.15.225-.387.3t-.463 0t-.375-.262");
}

</style>
