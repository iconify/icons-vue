<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qurko8bwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qurko8bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:locked-chest" /></template>
