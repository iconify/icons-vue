<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwgbuvb-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wwgbuvb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cave-entrance" /></template>
