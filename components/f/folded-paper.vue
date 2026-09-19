<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpwu43r9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wpwu43r9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:folded-paper" /></template>
