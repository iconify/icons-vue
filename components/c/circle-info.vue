<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tnrc7_bry.css';
import '../../css/y/yjt-ee8as.css';
import '../../css/h/hrhhzjb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tnrc7_bry"/><path class="yjt-ee8as"/><path class="hrhhzjb2t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-info" /></template>
