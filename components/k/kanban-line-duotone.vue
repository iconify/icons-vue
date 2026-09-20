<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cv_bv5bue.css';
import '../../css/f/f67y05bux.css';
import '../../css/n/n7itbbc5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cv_bv5bue"/><path class="f67y05bux"/><path class="n7itbbc5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:kanban-line-duotone" /></template>
