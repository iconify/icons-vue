<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k6s0dnb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-top-left-20-regular" /></template>
<style>
.k6s0dnb4f {
  fill: currentColor;
  d: path("M7.072 9.444a.5.5 0 0 0 .99.145l.086-.587h1.24l-.066.442a.5.5 0 0 0 .99.145l.086-.587H11a.5.5 0 0 0 0-1h-.456l.22-1.5h.736a.5.5 0 0 0 0-1h-.59l.137-.93a.5.5 0 0 0-.99-.144L9.9 5.502H8.66l.137-.93a.5.5 0 0 0-.99-.144L7.65 5.502H7a.5.5 0 0 0 0 1h.503l-.22 1.5H6.5a.5.5 0 0 0 0 1h.637zm2.681-2.942l-.22 1.5H8.295l.22-1.5zM6 2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm0 1h8a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1");
}

</style>
