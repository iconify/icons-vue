<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6i2682uu.css';
import '../../css/x/xai0083ma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t6i2682uu"/><path class="xai0083ma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:entertainment-events-hobbies-board-game-dice" /></template>
