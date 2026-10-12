<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v271sd3za.css';
import '../../css/r/rx2f-xb4d.css';
import '../../css/o/oe608fbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v271sd3za"/><path class="rx2f-xb4d"/><path class="oe608fbuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:fan-duotone" /></template>
