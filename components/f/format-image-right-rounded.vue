<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0wtppb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-image-right-rounded" /></template>
<style>
.p0wtppb8i {
  fill: currentColor;
  d: path("M12.308 16.25q-.343 0-.576-.232t-.232-.576V8.558q0-.343.232-.576t.576-.232h6.884q.344 0 .576.232t.232.576v6.884q0 .344-.232.576t-.576.232zM4.5 20q-.213 0-.356-.144T4 19.499t.144-.356T4.5 19h15q.213 0 .356.144t.144.357t-.144.356T19.5 20zm0-3.75q-.213 0-.356-.144T4 15.749t.144-.356t.356-.143h4.116q.212 0 .356.144t.144.357t-.144.356t-.356.143zm0-3.75q-.213 0-.356-.144T4 11.999t.144-.356t.356-.143h4.116q.212 0 .356.144t.144.357t-.144.356t-.356.143zm0-3.75q-.213 0-.356-.144T4 8.249t.144-.356t.356-.143h4.116q.212 0 .356.144t.144.357t-.144.356t-.356.143zM4.5 5q-.213 0-.356-.144T4 4.499t.144-.356T4.5 4h15q.213 0 .356.144t.144.357t-.144.356T19.5 5z");
}

</style>
