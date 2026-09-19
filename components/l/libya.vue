<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqseh9bgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cqseh9bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:libya" /></template>
