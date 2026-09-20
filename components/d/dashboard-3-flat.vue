<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/l/lyvgkurko.css';
import '../../css/c/cxvx_ubwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="lyvgkurko"/><path class="cxvx_ubwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:dashboard-3-flat" /></template>
