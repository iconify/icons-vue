<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/b/b53r-kbxl.css';
import '../../css/x/x_6_7pssw.css';
import '../../css/w/w-zh29bfx.css';
import '../../css/t/ttah5ul5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="b53r-kbxl"/><path class="x_6_7pssw"/><path class="w-zh29bfx"/><path class="ttah5ul5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:design-process-drawing-board-education" /></template>
