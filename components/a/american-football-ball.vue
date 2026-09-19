<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htd5qgbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="htd5qgbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:american-football-ball" /></template>
