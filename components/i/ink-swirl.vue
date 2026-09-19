<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr1gtybqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lr1gtybqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ink-swirl" /></template>
