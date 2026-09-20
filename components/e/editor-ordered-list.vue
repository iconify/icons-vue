<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-1tfybvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f-1tfybvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:editor-ordered-list" /></template>
