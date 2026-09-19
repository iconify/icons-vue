<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo856qbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uo856qbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:floating-crystal" /></template>
