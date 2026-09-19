<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnfg8ei_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fnfg8ei_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:keyboard" /></template>
