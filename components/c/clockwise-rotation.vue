<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzqo1xb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lzqo1xb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:clockwise-rotation" /></template>
