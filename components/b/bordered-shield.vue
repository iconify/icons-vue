<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm37cybfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pm37cybfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bordered-shield" /></template>
