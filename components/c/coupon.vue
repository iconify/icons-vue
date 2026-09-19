<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/l/l_ysdhbcq.css';
import '../../css/z/zh3_mmb6e.css';
import '../../css/y/yl8nvnbzd.css';
import '../../css/m/msx3sr11t.css';
import '../../css/d/duiqvnbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="l_ysdhbcq"/><path class="zh3_mmb6e"/><path class="yl8nvnbzd"/><path class="msx3sr11t"/><path class="duiqvnbvk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:coupon" /></template>
