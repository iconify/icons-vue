<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j9_3tq4pv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-up-left-48-regular" /></template>
<style>
.j9_3tq4pv {
  fill: currentColor;
  d: path("M35.5 40.75a1.25 1.25 0 1 0 2.5 0v-18.5A7.25 7.25 0 0 0 30.75 15H12.582l7.04-6.854a1.25 1.25 0 0 0-1.744-1.792l-9.5 9.25a1.25 1.25 0 0 0 0 1.792l9.5 9.25a1.25 1.25 0 0 0 1.744-1.792L12.069 17.5H30.75a4.75 4.75 0 0 1 4.75 4.75z");
}

</style>
