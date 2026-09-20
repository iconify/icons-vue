<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs8vkab7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-textdirection-r-to-l-sharp" /></template>
<style>
.zs8vkab7l {
  fill: currentColor;
  d: path("M10.135 14.5V9.73h-.443q-1.4 0-2.373-.982t-.973-2.382t.973-2.383T9.692 3h6.231v1h-1.884v10.5h-1V4h-1.905v10.5zm-4.239 3.827l1.985 1.965l-.708.708L4 17.808l3.173-3.174l.727.728l-1.984 1.965H20v1z");
}

</style>
