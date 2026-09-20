<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/n/n9mlm_otl.css';
import '../../css/d/d9oh6rbog.css';
import '../../css/c/cxnw3fbqh.css';
import '../../css/h/hjf31hb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="n9mlm_otl"/><path class="d9oh6rbog"/><path class="cxnw3fbqh"/><path class="hjf31hb1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:city-hall-flat" /></template>
