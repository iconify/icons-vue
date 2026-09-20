<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/mgj_-5kho.css';
import '../../css/t/twkjmwb_m.css';
import '../../css/o/oghttxkxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="mgj_-5kho"/><path class="twkjmwb_m"/><path class="oghttxkxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:barcode-view-price" /></template>
