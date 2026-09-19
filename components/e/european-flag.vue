<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms4wiabgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ms4wiabgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:european-flag" /></template>
