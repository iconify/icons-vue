<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/o/ogrq2b4bv.css';
import '../../css/c/cnukg4a-h.css';
import '../../css/d/d6k0ten6d.css';
import '../../css/d/d8hrn7boe.css';
import '../../css/l/l4jyliu5q.css';
import '../../css/e/e1t_o7bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ogrq2b4bv"/><path class="cnukg4a-h"/><path class="d6k0ten6d"/><path class="d8hrn7boe"/><path class="l4jyliu5q"/><path class="e1t_o7bfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:app-window-expand" /></template>
