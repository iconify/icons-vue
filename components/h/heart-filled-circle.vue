<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/d/d9x5vte3y.css';
import '../../css/x/xrgx2dblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="d9x5vte3y"/><path class="xrgx2dblx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:heart-filled-circle" /></template>
