<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zh66-hbof.css';
import '../../css/t/t69zavbbw.css';
import '../../css/v/v93r2imrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="zh66-hbof"/><path class="t69zavbbw"/><path class="v93r2imrg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:app-window-bookmark" /></template>
