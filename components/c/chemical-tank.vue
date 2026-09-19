<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5crd0brz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m5crd0brz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chemical-tank" /></template>
