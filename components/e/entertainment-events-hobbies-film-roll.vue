<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-th10mjr.css';
import '../../css/r/rndt691qq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n-th10mjr"/><path class="rndt691qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:entertainment-events-hobbies-film-roll" /></template>
