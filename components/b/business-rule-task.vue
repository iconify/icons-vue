<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/looy1fptd.css';
import '../../css/h/hcvtbmbxo.css';
import '../../css/d/dsg53ebnk.css';
import '../../css/y/yzfvx79qi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2000,"height":2000};
const content = `<g transform="translate(0 947.638)"><rect class="looy1fptd"/><path class="hcvtbmbxo"/><path class="dsg53ebnk"/><path class="yzfvx79qi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:business-rule-task" /></template>
