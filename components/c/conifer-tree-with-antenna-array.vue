<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le202y2fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="le202y2fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:conifer-tree-with-antenna-array" /></template>
