<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/k/kxgqrsb3g.css';
import '../../css/a/ab06w6wfc.css';
import '../../css/h/hv6qyvkuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="kxgqrsb3g"/><path class="ab06w6wfc"/><path class="hv6qyvkuz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:bandage" /></template>
