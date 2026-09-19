<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9ybwzbob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d9ybwzbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:flash-grenade" /></template>
