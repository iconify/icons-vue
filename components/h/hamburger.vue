<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khgs00bjt.css';
import '../../css/n/ngyi29bdb.css';
import '../../css/r/rxyiwtdxn.css';
import '../../css/m/m1lbx02vh.css';
import '../../css/v/vlubo49by.css';
import '../../css/q/qy75zbb9g.css';
import '../../css/b/byj6-ca8o.css';
import '../../css/z/zd-igubsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="khgs00bjt"/><path class="ngyi29bdb"/><ellipse class="rxyiwtdxn"/><ellipse class="m1lbx02vh"/><path class="vlubo49by"/><path class="qy75zbb9g"/><path class="byj6-ca8o"/><path class="zd-igubsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:hamburger" /></template>
