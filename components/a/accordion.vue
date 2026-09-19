<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz0yqlb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hz0yqlb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:accordion" /></template>
