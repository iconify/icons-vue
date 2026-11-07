<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/y8wn08zhi.css';
import '../../css/m/mnjv0ybzu.css';
import '../../css/a/af53pzb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y8wn08zhi"/><path class="mnjv0ybzu"/><path class="af53pzb1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-top-line-duotone" /></template>
