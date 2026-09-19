<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2enxbbjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y2enxbbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bird-mask" /></template>
