<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyr5jws7y.css';
import '../../css/r/rf4ztnb7f.css';
import '../../css/d/d4bfwebii.css';
import '../../css/p/p04d40b1j.css';
import '../../css/o/o_5gryb3v.css';
import '../../css/l/ljac3j5dx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><linearGradient id="SVGoyidRdFK" x1="184" x2="328" y1="131.3" y2="380.7" gradientUnits="userSpaceOnUse"><stop offset="0" class="jyr5jws7y"/><stop offset=".5" class="jyr5jws7y"/><stop offset="1" class="rf4ztnb7f"/></linearGradient></defs><circle fill="url(#SVGoyidRdFK)" class="d4bfwebii"/><path class="p04d40b1j"/><circle class="o_5gryb3v"/><path class="ljac3j5dx"><animateTransform attributeName="transform" calcMode="spline" dur="6s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1; .42, 0, .58, 1; .42, 0, .58, 1; .42, 0, .58, 1; .42, 0, .58, 1" keyTimes="0; .17; .25; .42; .5; .67; 1" repeatCount="indefinite" type="rotate" values="-54 256 256; -15 256 256; -36 256 256; 36 256 256; 10 256 256; 115 256 256; -54 256 256"/></path>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:barometer-fill" /></template>
