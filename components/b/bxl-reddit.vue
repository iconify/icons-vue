<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyprt8xil.css';
import '../../css/c/czi-3ob_q.css';
import '../../css/u/u_tnrpbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="jyprt8xil"/><path class="czi-3ob_q"/><path class="u_tnrpbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-reddit" /></template>
