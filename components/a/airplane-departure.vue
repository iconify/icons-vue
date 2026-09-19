<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo7obrd1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qo7obrd1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:airplane-departure" /></template>
