<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/t/t366rs_zx.css';
import '../../css/k/kjzre3jgv.css';
import '../../css/x/xma6_zbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="t366rs_zx"/><rect class="kjzre3jgv"/><path class="xma6_zbrt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:bank-card-one" /></template>
