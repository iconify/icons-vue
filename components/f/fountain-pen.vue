<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxsh1zboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wxsh1zboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fountain-pen" /></template>
