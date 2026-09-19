<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oeqjc6bxu.css';
import '../../css/w/w6i9gcqco.css';
import '../../css/e/en701kbcf.css';
import '../../css/x/x05er1ebx.css';
import '../../css/k/kznva-0mg.css';
import '../../css/v/v9z5chbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oeqjc6bxu"/><circle class="w6i9gcqco"/><circle class="en701kbcf"/><circle class="x05er1ebx"/><path class="kznva-0mg"/><path class="v9z5chbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:forecast-hail-30" /></template>
