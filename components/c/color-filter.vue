<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/w/wascf2ujt.css';
import '../../css/w/wee2qvrei.css';
import '../../css/t/timostb6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wascf2ujt"/><path class="wee2qvrei"/><path class="timostb6x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:color-filter" /></template>
