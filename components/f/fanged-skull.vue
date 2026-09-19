<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m87kksb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m87kksb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fanged-skull" /></template>
