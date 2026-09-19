<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/p/puo6m7bvm.css';
import '../../css/b/bmiu8w0sc.css';
import '../../css/c/cmsqj627t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="puo6m7bvm"/><path class="bmiu8w0sc"/><path class="cmsqj627t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:fingerprint" /></template>
