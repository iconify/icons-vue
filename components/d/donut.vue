<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqon8bbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wqon8bbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:donut" /></template>
