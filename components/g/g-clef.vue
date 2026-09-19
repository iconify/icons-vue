<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj1q6wbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vj1q6wbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:g-clef" /></template>
