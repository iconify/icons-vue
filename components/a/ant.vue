<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt9ixm04t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nt9ixm04t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ant" /></template>
