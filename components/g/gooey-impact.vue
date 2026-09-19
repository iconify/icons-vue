<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmknib4fq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mmknib4fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gooey-impact" /></template>
