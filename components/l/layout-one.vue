<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/x/xhdah4bbl.css';
import '../../css/a/am1igebwo.css';
import '../../css/y/yeo6-kifb.css';
import '../../css/q/qyy9o_btf.css';
import '../../css/l/l6pgklkvy.css';
import '../../css/y/yfm2a_b8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="xhdah4bbl"/><path class="am1igebwo"/><path class="yeo6-kifb"/><path class="qyy9o_btf"/><path class="l6pgklkvy"/><path class="yfm2a_b8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:layout-one" /></template>
