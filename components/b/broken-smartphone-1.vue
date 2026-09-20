<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/o/o0iveosml.css';
import '../../css/x/x3gn12ylu.css';
import '../../css/o/ozkkt8zvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="o0iveosml"/><path class="x3gn12ylu"/><path class="ozkkt8zvi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:broken-smartphone-1" /></template>
