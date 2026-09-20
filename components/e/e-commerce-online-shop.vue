<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zuenioh2k.css';
import '../../css/d/dg3f_fyeb.css';
import '../../css/y/ynzc3ibvs.css';
import '../../css/e/ehreetbpx.css';
import '../../css/i/io0rngbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="zuenioh2k"/><path class="dg3f_fyeb"/><path class="ynzc3ibvs"/><path class="ehreetbpx"/><path class="io0rngbwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:e-commerce-online-shop" /></template>
