<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni33p6btq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ni33p6btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hydra-shot" /></template>
