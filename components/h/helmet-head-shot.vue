<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak5e5k5fa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ak5e5k5fa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:helmet-head-shot" /></template>
