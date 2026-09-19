<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxdtobcxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xxdtobcxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lightning-flame" /></template>
