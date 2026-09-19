<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9-d4cb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s9-d4cb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hunter-eyes" /></template>
