<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/x/x2d1mxb0y.css';
import '../../css/z/zlmlysc6g.css';
import '../../css/u/urcv4fbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="x2d1mxb0y"/><path class="zlmlysc6g"/><path class="urcv4fbrt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:garbage-throw" /></template>
