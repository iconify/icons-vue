<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozf1p_y8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ozf1p_y8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ice-golem" /></template>
