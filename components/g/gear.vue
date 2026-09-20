<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/m/mgpqpcbbs.css';
import '../../css/t/tdy8om3sr.css';
import '../../css/r/r-3cp4o3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="mgpqpcbbs"/><path class="tdy8om3sr"/><path class="r-3cp4o3r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:gear" /></template>
