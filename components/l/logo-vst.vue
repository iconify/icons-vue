<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/h/hygzc7f2b.css';
import '../../css/d/dxvxrfbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="n1lsf0bnc"><path class="hygzc7f2b"/><path class="dxvxrfbem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:logo-vst" /></template>
