<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xs--b7q-p.css';
import '../../css/z/zrp9frbsy.css';
import '../../css/l/lqml3acji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xs--b7q-p"/><path class="zrp9frbsy"/><path class="lqml3acji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:archive" /></template>
