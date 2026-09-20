<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/y/yy0kmdbfn.css';
import '../../css/b/byeqgth4o.css';
import '../../css/d/d-mdo3b_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="yy0kmdbfn"/><path class="byeqgth4o"/><path class="d-mdo3b_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:fax-machine-paper-print" /></template>
