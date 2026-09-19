<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ree4tyblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ree4tyblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:american-football-player" /></template>
