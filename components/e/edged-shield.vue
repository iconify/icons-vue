<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7fq-fc7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j7fq-fc7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:edged-shield" /></template>
