<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wo-8srbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-enter-up-24-regular" /></template>
<style>
.wo-8srbyr {
  fill: currentColor;
  d: path("M20 21.25a.75.75 0 0 1-.75.75h-6.5A3.75 3.75 0 0 1 9 18.25V4.587l-3.72 3.72a.75.75 0 0 1-.976.072l-.084-.072a.75.75 0 0 1-.073-.977l.073-.084l5-5a.75.75 0 0 1 .976-.073l.084.073l5 5a.75.75 0 0 1-.976 1.133l-.084-.072l-3.72-3.72v13.665a2.25 2.25 0 0 0 2.096 2.244l.154.006h6.5a.75.75 0 0 1 .75.75");
}

</style>
