<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/a/aw1utkkeq.css';
import '../../css/t/t2k3-abcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2000,"height":2000};
const content = `<g class="pr52f_b5y"><path class="aw1utkkeq"/><path class="t2k3-abcp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:data-input" /></template>
