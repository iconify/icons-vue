<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5g7j806z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f5g7j806z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:jigsaw-box" /></template>
