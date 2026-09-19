<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/w/w94kgrhdl.css';
import '../../css/a/am6of0txh.css';
import '../../css/q/qdc63jnsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="w94kgrhdl"/><path class="am6of0txh"/><path class="qdc63jnsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:histogram" /></template>
