<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="um9_2hbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:bluetooth-disabled-20-regular" /></template>
<style>
.um9_2hbaa {
  fill: currentColor;
  d: path("m13.5 14.207l3.646 3.647a.5.5 0 0 0 .708-.708l-15-15a.5.5 0 1 0-.708.708L9 9.707v.066l-3.83 3.35a.5.5 0 0 0 .66.753L9 11.102V17.5a.5.5 0 0 0 .854.354zm.33-7.33L11.251 9.13l-.708-.709l2.224-1.946L10 3.707V7.88l-1-1V2.5a.5.5 0 0 1 .854-.354l4 4a.5.5 0 0 1-.025.73M10 11.101l2.768 2.422L10 16.293z");
}

</style>
