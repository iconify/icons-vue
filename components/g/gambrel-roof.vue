<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aegl-dfiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gambrel-roof" /></template>
<style>
.aegl-dfiy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 11.485v7.265q0 2.5 2.5 2.5h13.5q2.5 0 2.5-2.5v-7.264q.001-.693-.356-1.288l-2.471-4.117q-.401-.667-1.109-.989l-4.28-1.946q-1.034-.47-2.068 0l-4.28 1.946q-.708.322-1.109.989l-2.471 4.117q-.357.595-.356 1.287M12 18.561L9.53 21.03q-.105.106-.243.163T9 21.25t-.287-.057t-.243-.163q-.106-.105-.163-.243T8.25 20.5v-6.004q.001-.148.058-.285t.162-.241q.105-.106.243-.163T9 13.75h6q.149 0 .287.057t.243.163q.106.105.163.243t.057.287v6q0 .149-.057.287t-.163.243v.001l-.006.006h-.001q-.105.103-.24.158q-.136.055-.283.055q-.149 0-.287-.057t-.243-.163zm1.061-1.061l1.189 1.189v-2.378zm.128-2.25L12 16.439l-1.189-1.189zm-2.25 2.25L9.75 18.689v-2.378z");
}

</style>
