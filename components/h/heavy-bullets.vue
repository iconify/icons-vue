<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/setq1eb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="setq1eb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:heavy-bullets" /></template>
