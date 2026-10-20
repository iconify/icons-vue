<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnovs-bfk.css';
import '../../css/o/ow9eo7bnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bnovs-bfk"/><path class="ow9eo7bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lightbulb-sparkle-20" /></template>
