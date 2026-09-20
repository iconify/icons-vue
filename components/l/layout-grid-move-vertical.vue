<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/y/y2ls4efbx.css';
import '../../css/t/td4pmbm2c.css';
import '../../css/v/vbgobacsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><rect class="y2ls4efbx"/><rect class="td4pmbm2c"/><path class="vbgobacsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:layout-grid-move-vertical" /></template>
