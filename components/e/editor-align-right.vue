<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv1o7x2xo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rv1o7x2xo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:editor-align-right" /></template>
