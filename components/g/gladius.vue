<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3p4cvbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d3p4cvbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gladius" /></template>
