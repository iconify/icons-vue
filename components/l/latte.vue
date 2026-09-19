<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o58hkebvg.css';
import '../../css/o/oscabebss.css';
import '../../css/i/ijtuyxbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="o58hkebvg"><path class="oscabebss"/><path class="ijtuyxbwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:latte" /></template>
