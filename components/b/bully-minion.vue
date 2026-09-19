<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1ciw5bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g1ciw5bfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bully-minion" /></template>
