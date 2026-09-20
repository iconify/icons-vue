<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em5qjuh7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="em5qjuh7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-down-left-box" /></template>
