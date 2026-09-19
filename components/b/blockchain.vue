<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/s/svjez5bnv.css';
import '../../css/t/todid_jkm.css';
import '../../css/j/j9j20gb6q.css';
import '../../css/x/xw6xfpouc.css';
import '../../css/a/a73yutbfd.css';
import '../../css/q/qngn3tbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="svjez5bnv"/><path class="todid_jkm"/><path class="j9j20gb6q"/><circle class="xw6xfpouc"/><circle class="a73yutbfd"/><circle class="qngn3tbqy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:blockchain" /></template>
