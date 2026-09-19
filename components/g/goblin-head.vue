<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weedt_blz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="weedt_blz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:goblin-head" /></template>
