<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxme_acpu.css';
import '../../css/l/l01hkrxue.css';
import '../../css/m/mb3yi70mk.css';
import '../../css/v/v6b46jg0g.css';
import '../../css/h/hbuw06f9w.css';
import '../../css/g/gdcfuvfdh.css';
import '../../css/r/r4edr4btg.css';
import '../../css/b/bsqkpn2ax.css';
import '../../css/c/c8t690wsk.css';
import '../../css/d/doku__8gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gxme_acpu"/><path class="l01hkrxue"/><path class="mb3yi70mk"/><path class="v6b46jg0g"/><path class="hbuw06f9w"/><path class="gdcfuvfdh"/><path class="r4edr4btg"/><path class="bsqkpn2ax"/><path class="c8t690wsk"/><path class="doku__8gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:fuelpump" /></template>
