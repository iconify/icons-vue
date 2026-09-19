<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h2k4rcbma.css';
import '../../css/n/npblxp04p.css';
import '../../css/n/n3n5idbee.css';
import '../../css/u/ugfymdbif.css';
import '../../css/a/axw_ngf8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="h2k4rcbma"/><path class="npblxp04p"/><path class="n3n5idbee"/><path class="ugfymdbif"/><path class="axw_ngf8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:expand-print" /></template>
