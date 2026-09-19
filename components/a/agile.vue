<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/o/odm-21boh.css';
import '../../css/n/n6i2qcb0p.css';
import '../../css/u/uxgpy7ntg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="odm-21boh"/><path class="n6i2qcb0p"/><path class="uxgpy7ntg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:agile" /></template>
