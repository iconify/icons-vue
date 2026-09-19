<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv4h_ojov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xv4h_ojov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dreadnought" /></template>
