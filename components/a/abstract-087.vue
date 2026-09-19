<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irdde39cb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="irdde39cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-087" /></template>
