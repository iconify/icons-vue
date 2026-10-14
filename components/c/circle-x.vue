<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/d/daqoe1b8w.css';
import '../../css/h/hl2dq2b3a.css';
import '../../css/b/b61j3abxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="daqoe1b8w"/><path class="hl2dq2b3a"/><path class="b61j3abxr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:circle-x" /></template>
