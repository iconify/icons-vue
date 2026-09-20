<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8t08ubig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="g8t08ubig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-q" /></template>
