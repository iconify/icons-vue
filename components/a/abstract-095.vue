<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qoyw6ibyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qoyw6ibyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-095" /></template>
