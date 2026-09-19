<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/j/jt23tkppp.css';
import '../../css/h/hrmz_5b-w.css';
import '../../css/o/orc4cutqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jt23tkppp"/><path class="hrmz_5b-w"/><path class="orc4cutqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:graph-infected-increasing" /></template>
