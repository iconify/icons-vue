<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndv3dvc2g.css';
import '../../css/f/fi80utbym.css';
import '../../css/q/qyvlp9bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ndv3dvc2g"/><path class="fi80utbym"/><path class="qyvlp9bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:archery-20" /></template>
