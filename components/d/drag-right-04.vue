<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/zng09ib1c.css';
import '../../css/q/qkyarlbcy.css';
import '../../css/n/np86eoxaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zng09ib1c"/><path class="qkyarlbcy"/><path class="np86eoxaz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:drag-right-04" /></template>
