<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/g528lbb8m.css';
import '../../css/x/xsnx6db8b.css';
import '../../css/p/pskxq8kjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="g528lbb8m"/><path class="xsnx6db8b"/><path class="pskxq8kjn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:drag-left-03" /></template>
