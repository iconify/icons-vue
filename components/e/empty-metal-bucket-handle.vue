<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp-4tryuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kp-4tryuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:empty-metal-bucket-handle" /></template>
