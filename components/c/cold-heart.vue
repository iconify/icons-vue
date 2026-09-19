<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i67g3mcha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i67g3mcha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cold-heart" /></template>
