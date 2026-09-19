<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygs-idd4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ygs-idd4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:candles" /></template>
