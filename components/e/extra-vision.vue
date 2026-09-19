<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dryjefbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dryjefbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:extra-vision" /></template>
