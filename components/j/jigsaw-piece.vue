<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo25o29sc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vo25o29sc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:jigsaw-piece" /></template>
