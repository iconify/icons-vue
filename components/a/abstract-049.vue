<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgh5s1vxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lgh5s1vxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-049" /></template>
