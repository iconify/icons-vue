<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/q/qvw8cmbxf.css';
import '../../css/g/gf99-6-mc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="qvw8cmbxf"/><path class="gf99-6-mc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:file-check" /></template>
