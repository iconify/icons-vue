<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qxj4zkbbb.css';
import '../../css/f/fbyg_kb_c.css';
import '../../css/y/ydvqm7-lm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qxj4zkbbb"/><path class="fbyg_kb_c"/><path class="ydvqm7-lm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:car-taxi-1-flat" /></template>
