<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nq3ucobtl.css';
import '../../css/x/xz914h8mb.css';
import '../../css/z/zn-yurbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nq3ucobtl"/><path class="xz914h8mb"/><path class="zn-yurbog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-dot-open-linear" /></template>
