<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lyoovxudk.css';
import '../../css/l/lnct-eb9z.css';
import '../../css/n/ns8r1ybrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lyoovxudk"/><path class="lnct-eb9z"/><path class="ns8r1ybrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-tree-line-duotone" /></template>
