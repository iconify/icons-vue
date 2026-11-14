<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="om1gqubye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ice-core" /></template>
<style>
.om1gqubye {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2.25q-4.75 0-4.75 2.25v15q0 2.25 4.75 2.25t4.75-2.25v-15q0-2.25-4.75-2.25m3.25 11.164l-6.5 1.625v-3.917l6.5-1.218zm-6.5 3.172l6.5-1.625V19.5q0 .75-3.25.75t-3.25-.75zm6.5-10.268v2.06l-6.5 1.218V6.318q1.169.432 3.25.432t3.25-.432");
}

</style>
