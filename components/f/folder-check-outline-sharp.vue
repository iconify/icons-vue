<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quz5yvbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-check-outline-sharp" /></template>
<style>
.quz5yvbis {
  fill: currentColor;
  d: path("m10.85 15.864l4.938-4.964l-.688-.688l-4.25 4.23l-2.125-2.105l-.713.713zM3 19V5h6.596l2 2H21v12zm1-1h16V8h-8.806l-2-2H4zm0 0V6z");
}

</style>
