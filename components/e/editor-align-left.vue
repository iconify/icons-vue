<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p40nu0x8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p40nu0x8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:editor-align-left" /></template>
