<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm2moacxj.css';
import '../../css/c/cr265u0om.css';
import '../../css/b/b732rrycy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm2moacxj"/><rect class="cr265u0om"><animateTransform attributeName="transform" dur="9s" repeatCount="indefinite" type="rotate" values="0 12 12;360 12 12"/></rect><rect class="b732rrycy"><animateTransform attributeName="transform" dur="0.75s" repeatCount="indefinite" type="rotate" values="0 12 12;360 12 12"/></rect>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="svg-spinners:clock" /></template>
