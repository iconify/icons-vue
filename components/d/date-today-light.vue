<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nigx2wbdb.css';
import '../../css/h/htjepabmz.css';
import '../../css/q/qtkdtxbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><rect class="nigx2wbdb"/><path class="htjepabmz"/><path class="qtkdtxbkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:date-today-light" /></template>
