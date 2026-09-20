<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/a/ariqabb3m.css';
import '../../css/p/p3xi1cbyh.css';
import '../../css/h/hcf_tsbst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ariqabb3m"/><path class="p3xi1cbyh"/><path class="hcf_tsbst"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:content-browser-edit" /></template>
