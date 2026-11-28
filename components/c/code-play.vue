<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aeh87fbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aeh87fbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:code-play" /></template>
