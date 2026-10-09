<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2tojgbsp.css';
import '../../css/z/z8jy6p5aj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n2tojgbsp"/><path class="z8jy6p5aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flow-battery-20" /></template>
