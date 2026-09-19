<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b188s4buy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b188s4buy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:key-card" /></template>
