<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3ct_9bhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1056,"height":1408};
const content = `<g transform="translate(0 1408) scale(1 -1)"><path class="t3ct_9bhw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:level-down" /></template>
