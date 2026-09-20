<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/m/mu060xb3h.css';
import '../../css/r/rcn884par.css';
import '../../css/e/e2ptqqbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mu060xb3h"/><path class="rcn884par"/><path class="e2ptqqbrs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:grid-edit" /></template>
