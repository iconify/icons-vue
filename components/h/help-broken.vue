<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/aqhok2bbj.css';
import '../../css/w/wtr0t5bay.css';
import '../../css/x/xo0gn7bpl.css';
import '../../css/z/zkjcpqlzm.css';
import '../../css/s/sm0uzcbjt.css';
import '../../css/j/jed98nbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="aqhok2bbj"/><path class="wtr0t5bay"/><path class="xo0gn7bpl"/><path class="zkjcpqlzm"/><path class="sm0uzcbjt"/><path class="jed98nbpx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:help-broken" /></template>
