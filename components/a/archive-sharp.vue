<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhwxe54iq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:archive-sharp" /></template>
<style>
.hhwxe54iq {
  fill: currentColor;
  d: path("m12 18l4-4l-1.4-1.4l-1.6 1.6V10h-2v4.2l-1.6-1.6L8 14zm-9 3V5.8L5.3 3h13.4L21 5.8V21zM5.4 6h13.2l-.85-1H6.25z");
}

</style>
