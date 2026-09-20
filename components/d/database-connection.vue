<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/i/ib0bfjs-x.css';
import '../../css/a/agtdgvboj.css';
import '../../css/p/phwb8ebnx.css';
import '../../css/g/gu1jjjtbk.css';
import '../../css/w/wa8a2-4kk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ib0bfjs-x"/><path class="agtdgvboj"/><path class="phwb8ebnx"/><path class="gu1jjjtbk"/><path class="wa8a2-4kk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:database-connection" /></template>
