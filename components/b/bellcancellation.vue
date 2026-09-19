<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1d3s3bsn.css';
import '../../css/l/lqbsjrb1w.css';
import '../../css/o/o676dwbcr.css';
import '../../css/u/u-r-ieuow.css';
import '../../css/i/i2d_gzgyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u1d3s3bsn"/><path class="lqbsjrb1w"/><path class="o676dwbcr"/><path class="u-r-ieuow"/><path class="i2d_gzgyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:bellcancellation" /></template>
