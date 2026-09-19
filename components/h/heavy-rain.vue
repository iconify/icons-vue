<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vf8oocclb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vf8oocclb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:heavy-rain" /></template>
