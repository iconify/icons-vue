<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7oslieck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c7oslieck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:drakkar-dragon" /></template>
