<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qss_jzvjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:electric-bolt-outline-sharp" /></template>
<style>
.qss_jzvjc {
  fill: currentColor;
  d: path("M7.673 21.02L11.712 14L4 13.096L15.25 2.981h1.116l-4.135 7.038l7.769.885L8.75 21.019zm2.839-3.003l7.179-6.369l-7.072-.792l2.902-4.906l-7.212 6.389l7.047.844zM12 11.981");
}

</style>
