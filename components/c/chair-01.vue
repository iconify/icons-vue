<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/o3bsa3b3l.css';
import '../../css/o/ognykqjii.css';
import '../../css/x/xzgh_vbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o3bsa3b3l"/><path class="ognykqjii"/><path class="xzgh_vbuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chair-01" /></template>
