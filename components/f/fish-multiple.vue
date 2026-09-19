<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyvdncc_g.css';
import '../../css/r/rn2kcz5al.css';
import '../../css/g/gnbroibpd.css';
import '../../css/g/g51crmbnr.css';
import '../../css/c/cb92fbcyb.css';
import '../../css/s/su8ov74lc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dyvdncc_g"/><circle class="rn2kcz5al"/><path class="gnbroibpd"/><circle class="g51crmbnr"/><circle class="cb92fbcyb"/><path class="su8ov74lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:fish-multiple" /></template>
