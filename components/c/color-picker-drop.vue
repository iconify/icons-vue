<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/n/noo63lbvs.css';
import '../../css/g/gldq60b_b.css';
import '../../css/w/wdxiyjbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="noo63lbvs"/><path class="gldq60b_b"/><path class="wdxiyjbdk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:color-picker-drop" /></template>
