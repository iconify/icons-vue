<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5ln-ibxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e5ln-ibxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:falling-eye" /></template>
