<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-hacabaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e-hacabaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:diploma" /></template>
