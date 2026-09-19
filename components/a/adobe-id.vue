<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhb8c01ug.css';
import '../../css/j/j8wdgmbqs.css';
import '../../css/n/np3_17o5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hhb8c01ug"><path class="j8wdgmbqs"/><path class="np3_17o5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:adobe-id" /></template>
