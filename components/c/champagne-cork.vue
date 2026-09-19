<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef14_207f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ef14_207f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:champagne-cork" /></template>
