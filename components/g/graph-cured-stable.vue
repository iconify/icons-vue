<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/h/h4fu5v_la.css';
import '../../css/l/lvhb8mgml.css';
import '../../css/e/emjm_bcem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h4fu5v_la"/><path class="lvhb8mgml"/><path class="emjm_bcem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:graph-cured-stable" /></template>
