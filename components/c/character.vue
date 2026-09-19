<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1y31mg3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d1y31mg3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:character" /></template>
