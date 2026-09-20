<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/f/fka5-chwr.css';
import '../../css/v/vz8f7c_9l.css';
import '../../css/q/q2bd4hbvs.css';
import '../../css/w/wjis5yb4j.css';
import '../../css/z/zn0ta-bnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="fka5-chwr"/><path class="vz8f7c_9l"/><path class="q2bd4hbvs"/><path class="wjis5yb4j"/><path class="zn0ta-bnf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:cleaning-man" /></template>
