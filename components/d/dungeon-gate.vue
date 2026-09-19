<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hoj1bbclk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hoj1bbclk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dungeon-gate" /></template>
