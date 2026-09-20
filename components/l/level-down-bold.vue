<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do0sxgbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="do0sxgbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:level-down-bold" /></template>
