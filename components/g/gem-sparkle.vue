<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xibuolb2y.css';
import '../../css/c/c85egjb-l.css';
import '../../css/a/ap9enlbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xibuolb2y"/><path class="c85egjb-l"/><path class="ap9enlbhu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:gem-sparkle" /></template>
