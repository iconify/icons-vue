<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/b/bv4j_vbwv.css';
import '../../css/w/wltzwqb8g.css';
import '../../css/t/td6-0hbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="bv4j_vbwv"/><path class="wltzwqb8g"/><path class="td6-0hbao"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:database-share" /></template>
