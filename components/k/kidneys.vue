<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztyz0qbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ztyz0qbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:kidneys" /></template>
