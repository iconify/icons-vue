<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdnyycc-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bookmark-check" /></template>
<style>
.cdnyycc-s {
  fill: currentColor;
  d: path("m10.95 13.289l4.239-4.239l-.714-.708l-3.525 3.544l-1.425-1.424l-.713.713zM6 19.5V5.616q0-.691.463-1.153T7.616 4h8.769q.69 0 1.153.463T18 5.616V19.5l-6-2.577z");
}

</style>
