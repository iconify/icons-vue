<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmml0cbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:line-start-diamond-outline-rounded" /></template>
<style>
.pmml0cbmn {
  fill: currentColor;
  d: path("M9 15.348L12.348 12L9 8.652L5.652 12zm-.565.856l-3.639-3.639q-.242-.242-.242-.565t.242-.565l3.638-3.639q.243-.242.566-.242t.566.242l3.703 3.704h7.154q.214 0 .357.143t.143.357t-.143.357t-.357.143h-7.154l-3.703 3.704q-.243.242-.566.242t-.565-.242M9 12");
}

</style>
