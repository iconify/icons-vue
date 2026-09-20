<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/h/hc5zd5brf.css';
import '../../css/a/a_pyc2bpc.css';
import '../../css/b/bnfq09b2d.css';
import '../../css/g/gyk0iu-vo.css';
import '../../css/i/iqiksqb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="hc5zd5brf"/><path class="a_pyc2bpc"/><path class="bnfq09b2d"/><path class="gyk0iu-vo"/><path class="iqiksqb_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:f-droid-logo" /></template>
