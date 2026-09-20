<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/d/dxcqicbbo.css';
import '../../css/l/lbvil20dt.css';
import '../../css/l/l6umjrccz.css';
import '../../css/m/m598ti66d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dxcqicbbo"/><path class="lbvil20dt"/><path class="l6umjrccz"/><path class="m598ti66d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:convert-card" /></template>
