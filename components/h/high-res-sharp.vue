<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz0jt2bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:high-res-sharp" /></template>
<style>
.wz0jt2bmh {
  fill: currentColor;
  d: path("M10 18.5h4V17h-2.5v-.75h2v-1.5h-2V14H14v-1.5h-4zm5 0h4.5V15h-3v-1h3v-1.5H15V16h3v1h-3zm-7.5-7H9V9.25h1.5v2.25H12v-6h-1.5v2.25H9V5.5H7.5zm7 0H16v-6h-1.5zM1 21V3h22v18zm3.5-2.5H6v-2h.6l.9 2H9l-.9-2.1q.375-.225.638-.587T9 15v-1q0-.625-.437-1.062T7.5 12.5h-3zM6 15v-1h1.5v1z");
}

</style>
