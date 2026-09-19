<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfai0kb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mfai0kb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:duel" /></template>
