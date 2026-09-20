<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp6x7xhme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jp6x7xhme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:editor-italic" /></template>
