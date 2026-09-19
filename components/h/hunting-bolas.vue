<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd4x53h2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fd4x53h2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hunting-bolas" /></template>
