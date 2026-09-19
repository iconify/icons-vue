<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc5crhb4x.css';
import '../../css/y/yno1x_b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wc5crhb4x"/><path class="yno1x_b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-hyper-protect-vs" /></template>
