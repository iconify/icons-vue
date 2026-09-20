<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zoa5qxt6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:approval-delegation-outline-sharp" /></template>
<style>
.zoa5qxt6q {
  fill: currentColor;
  d: path("M13.521 11.05L9.983 7.511l.713-.688l2.825 2.825l5.675-5.65l.689.688zm1.095 10.873L7 19.703V21H3v-8.154h6.373l7.358 2.693v1.615h4.865v2.615zM4 20h2v-6.154H4zm10.566.862l6.007-1.831v-.877h-6.921l-3.106-1.012l.331-.958l2.925.97h1.929v-.92l-6.515-2.388H7v4.808z");
}

</style>
