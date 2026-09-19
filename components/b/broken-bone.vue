<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjfg9214w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zjfg9214w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:broken-bone" /></template>
