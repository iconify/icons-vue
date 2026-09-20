<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/l/lvw-4wf-u.css';
import '../../css/e/eqp1polmy.css';
import '../../css/y/ya_ml8bfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="lvw-4wf-u"/><path class="eqp1polmy"/><path class="ya_ml8bfp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:desktop-action-monitor-remove" /></template>
