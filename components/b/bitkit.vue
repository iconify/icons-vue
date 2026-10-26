<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/l/l_e55p-ia.css';
import '../../css/y/yizg1nbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="l_e55p-ia"/><path class="yizg1nbwt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:bitkit" /></template>
