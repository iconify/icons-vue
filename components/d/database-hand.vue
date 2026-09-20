<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/h/hx9jwpb-t.css';
import '../../css/c/cb6hoeb9u.css';
import '../../css/c/cl_mzjtei.css';
import '../../css/m/mvrjg2bys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="hx9jwpb-t"/><path class="cb6hoeb9u"/><path class="cl_mzjtei"/><path class="mvrjg2bys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:database-hand" /></template>
