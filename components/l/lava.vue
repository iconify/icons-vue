<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag-b0_ben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ag-b0_ben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lava" /></template>
