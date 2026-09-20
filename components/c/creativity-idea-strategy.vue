<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/t/tvjpfuqws.css';
import '../../css/v/vgw_f6qab.css';
import '../../css/b/br1x7ltog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="tvjpfuqws"/><path class="vgw_f6qab"/><path class="br1x7ltog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:creativity-idea-strategy" /></template>
