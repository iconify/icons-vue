<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/id2aypzrn.css';
import '../../css/b/btnlk1maf.css';
import '../../css/u/umvgb2fhw.css';
import '../../css/c/cn2f9dbpj.css';
import '../../css/o/oc96mnvuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="id2aypzrn"/><path class="btnlk1maf wm-s"/><path class="umvgb2fhw wm-s"/><path class="cn2f9dbpj"/><path class="oc96mnvuf wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:globe-lock-duo" /></template>
