<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxthv2xzn.css';
import '../../css/o/o6zvk8buv.css';
import '../../css/l/lr_3epb6x.css';
import '../../css/r/r8ph69bil.css';
import '../../css/s/shbjhacsf.css';
import '../../css/v/v2t5oviwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pxthv2xzn"/><path class="o6zvk8buv"/><path class="lr_3epb6x"/><path class="r8ph69bil"/><path class="shbjhacsf"/><path class="v2t5oviwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:folding-home-light" /></template>
