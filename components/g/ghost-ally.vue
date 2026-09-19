<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb1-qkblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tb1-qkblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ghost-ally" /></template>
