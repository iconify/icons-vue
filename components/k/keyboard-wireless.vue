<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/l/ltmwlr7si.css';
import '../../css/j/jxcqzgbap.css';
import '../../css/p/pxku7lbxz.css';
import '../../css/t/ti5kg_b8s.css';
import '../../css/d/dwpi1dbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ltmwlr7si"/><path class="jxcqzgbap"/><path class="pxku7lbxz"/><path class="ti5kg_b8s"/><path class="dwpi1dbbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:keyboard-wireless" /></template>
