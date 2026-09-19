<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kid9qfb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kid9qfb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-4-hearts" /></template>
