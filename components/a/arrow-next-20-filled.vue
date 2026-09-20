<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g146hi8sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-next-20-filled" /></template>
<style>
.g146hi8sk {
  fill: currentColor;
  d: path("M13.75 4.75a.75.75 0 0 1 .743.648l.007.102v9a.75.75 0 0 1-1.493.102L13 14.5v-9a.75.75 0 0 1 .75-.75m-8.28.22a.75.75 0 0 1 .976-.073l.084.073l4.5 4.5a.75.75 0 0 1 .073.976l-.073.084l-4.5 4.5a.75.75 0 0 1-1.133-.976l.073-.084L9.44 10L5.47 6.03a.75.75 0 0 1 0-1.06");
}

</style>
