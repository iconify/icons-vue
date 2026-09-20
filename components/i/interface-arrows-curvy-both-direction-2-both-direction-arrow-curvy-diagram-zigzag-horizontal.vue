<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyo64f5ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="eyo64f5ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-curvy-both-direction-2-both-direction-arrow-curvy-diagram-zigzag-horizontal" /></template>
