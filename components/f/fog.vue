<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytmx3s51g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ytmx3s51g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:fog" /></template>
