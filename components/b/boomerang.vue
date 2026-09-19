<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7u88fbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q7u88fbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:boomerang" /></template>
