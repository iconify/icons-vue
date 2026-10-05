<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/x/xutqjtbzv.css';
import '../../css/n/ngkwocppj.css';
import '../../css/g/gll9pmo4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="xutqjtbzv"/><path class="ngkwocppj"/><path class="gll9pmo4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:layers" /></template>
