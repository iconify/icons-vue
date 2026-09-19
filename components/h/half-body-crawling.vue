<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya7id6pwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ya7id6pwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:half-body-crawling" /></template>
