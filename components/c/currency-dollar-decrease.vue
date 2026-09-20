<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/w/wn0mrybgi.css';
import '../../css/f/fq5-7dbbn.css';
import '../../css/r/rj-q30x7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="wn0mrybgi"/><path class="fq5-7dbbn"/><path class="rj-q30x7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:currency-dollar-decrease" /></template>
