<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvf4a8bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ad-group-off-outline-sharp" /></template>
<style>
.hvf4a8bid {
  fill: currentColor;
  d: path("M20.7 17.875L18.825 16H20V6H8.825l-2.7-2.7V2H22v15.875zm-.2 5.425L15.2 18H6V8.8L.7 3.5l1.4-1.4l19.8 19.8zM8 16h5.2L8 10.8zm-6 6V6h2v14h14v2zm11.475-11.35");
}

</style>
