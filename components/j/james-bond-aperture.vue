<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg32kgb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tg32kgb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:james-bond-aperture" /></template>
