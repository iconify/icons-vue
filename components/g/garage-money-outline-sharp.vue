<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pggn85bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:garage-money-outline-sharp" /></template>
<style>
.pggn85bnv {
  fill: currentColor;
  d: path("M4 20V4zm-1 1V3h18v8.846h-1V4H4v16h5.539v1zm3-3.5h1v-2h2.539v-1H7v-3h11v-.246L16.344 6.5H7.656L6 11.254zm1.304-7l1.046-3h7.3l1.046 3zm1.85 3.04q.23-.23.23-.54t-.23-.54t-.538-.23t-.54.23t-.23.54t.23.54t.54.23t.539-.23m4.982 6.576h5.727q.125-.506.474-.923t.854-.58v-1.996q-.505-.163-.854-.58t-.474-.922h-5.727q-.125.506-.474.923t-.855.58v1.996q.506.163.855.58t.474.922m3.656-1.707q.323-.322.323-.793t-.323-.794T17 16.5t-.793.322q-.323.322-.323.794q0 .47.323.793q.322.322.793.322t.793-.322M11.923 21v-6.77h10.154V21z");
}

</style>
