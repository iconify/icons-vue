<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/l/lp8lhlb1o.css';
import '../../css/s/sz7i2xb4j.css';
import '../../css/v/vupfj4bbw.css';
import '../../css/z/zjenxebue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="lp8lhlb1o"/><path class="sz7i2xb4j"/><path class="vupfj4bbw"/><path class="zjenxebue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:face-recognition" /></template>
