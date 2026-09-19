<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg3s3f--q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cg3s3f--q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:frozen-ring" /></template>
