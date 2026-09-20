<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4i2ew1ke.css';
import '../../css/i/ikn_sw-ck.css';
import '../../css/q/qadltybwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="v4i2ew1ke"/><g><circle class="ikn_sw-ck"/><circle class="qadltybwf"/><animateTransform attributeName="transform" calcMode="spline" dur="1s" keySplines=".36,.6,.31,1;.36,.6,.31,1" repeatCount="indefinite" type="rotate" values="0 12 12;180 12 12;360 12 12"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="svg-spinners:3-dots-rotate" /></template>
