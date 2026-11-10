<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w4ndr1_4b.css';
import '../../css/s/se0214bji.css';
import '../../css/a/acy_macas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w4ndr1_4b"/><path class="se0214bji"/><path class="acy_macas"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:file-edit" /></template>
