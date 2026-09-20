<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8z168b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ink-eraser-off" /></template>
<style>
.q8z168b0g {
  fill: currentColor;
  d: path("m19.833 21.26l-5.11-5.11L11.962 19H4.558l-1.414-1.413q-.478-.48-.491-1.137t.466-1.161l5.277-5.466l-5.655-5.656l.713-.713l17.092 17.092zm-3.016-7.254l-6.351-6.352l2.807-2.92q.479-.503 1.134-.494t1.133.489l4.09 4.09q.48.479.49 1.146q.009.668-.47 1.147z");
}

</style>
