<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in2f1jboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="in2f1jboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:heart-plus" /></template>
