<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/x/xltgi6s1j.css';
import '../../css/f/f0rmndbzt.css';
import '../../css/o/of8nq_0fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="xltgi6s1j"/><path class="f0rmndbzt"/><path class="of8nq_0fv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:camp" /></template>
