<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/x/x38mjom2y.css';
import '../../css/t/t_kavccpz.css';
import '../../css/m/ma-vyac-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="x38mjom2y"/><path class="t_kavccpz"/><path class="ma-vyac-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:cloudy-mostly" /></template>
