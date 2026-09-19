<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krqjo6bzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="krqjo6bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bunker-assault" /></template>
