<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cffl50b_w.css';
import '../../css/f/f7nm9cc1p.css';
import '../../css/e/ei2m3mbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cffl50b_w"/><path class="f7nm9cc1p"/><path class="ei2m3mbbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:composition-16-to-9" /></template>
