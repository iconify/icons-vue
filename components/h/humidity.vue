<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4f5e1b5a.css';
import '../../css/c/cphannb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVGTMGZ0bsS" viewBox="0 0 175 260.9"><path class="i4f5e1b5a"><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="6s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="scale" values="1 1; 1 .9; 1 1"/></path></symbol></defs><use width="175" height="260.9" href="#SVGTMGZ0bsS" transform="translate(168.4 123.18)"/><path class="cphannb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:humidity" /></template>
