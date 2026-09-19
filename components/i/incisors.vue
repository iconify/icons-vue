<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d96mkv88n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d96mkv88n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:incisors" /></template>
