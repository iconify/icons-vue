<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxwjpb_mr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-textdirection-r-to-l-outline-sharp" /></template>
<style>
.dxwjpb_mr {
  fill: currentColor;
  d: path("M10.135 14.5V9.73h-.443q-1.4 0-2.373-.982t-.973-2.382t.973-2.383T9.692 3h6.231v1h-1.884v10.5h-1V4h-1.905v10.5zm-4.239 3.827l1.985 1.965l-.708.708L4 17.808l3.173-3.174l.727.728l-1.984 1.965H20v1zm4.239-9.596V4h-.443q-.978 0-1.662.696q-.684.695-.684 1.672q0 .976.684 1.67q.684.693 1.662.693zm0-2.365");
}

</style>
