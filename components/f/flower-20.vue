<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jixfx1hdh.css';
import '../../css/r/ra1vsdwoa.css';
import '../../css/e/ep6j9gigt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jixfx1hdh"/><path class="ra1vsdwoa"/><path class="ep6j9gigt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flower-20" /></template>
