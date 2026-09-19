<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmfk8vyff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hmfk8vyff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:desert-skull" /></template>
