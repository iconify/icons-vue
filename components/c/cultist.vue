<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw01_5bhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vw01_5bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cultist" /></template>
