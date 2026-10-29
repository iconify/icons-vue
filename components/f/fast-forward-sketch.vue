<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nr6fqccxw.css';
import '../../css/z/zyqc9rfhb.css';
import '../../css/d/dzs1i5bjm.css';
import '../../css/l/lrmoo_osq.css';
import '../../css/t/tbtn-lyjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nr6fqccxw"/><path class="wm-k zyqc9rfhb"/><path class="dzs1i5bjm wm-a"/><path class="lrmoo_osq wm-k"/><path class="tbtn-lyjz wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:fast-forward-sketch" /></template>
