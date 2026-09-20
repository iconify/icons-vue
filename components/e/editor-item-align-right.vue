<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3sxgqb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l3sxgqb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:editor-item-align-right" /></template>
