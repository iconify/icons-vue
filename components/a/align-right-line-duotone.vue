<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hrhj5ybtt.css';
import '../../css/q/qblnn4bzv.css';
import '../../css/j/j6ohuicfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hrhj5ybtt"/><path class="qblnn4bzv"/><path class="j6ohuicfp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-right-line-duotone" /></template>
