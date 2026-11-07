<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nj09urbqm.css';
import '../../css/x/x2bk3cxln.css';
import '../../css/m/my2gg1bbn.css';
import '../../css/n/nm0c_vb4u.css';
import '../../css/s/s_921kb2k.css';
import '../../css/k/kdi5xyb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nj09urbqm"/><path class="x2bk3cxln"/><path class="my2gg1bbn"/><path class="nm0c_vb4u"/><path class="s_921kb2k"/><path class="kdi5xyb-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:balls-broken" /></template>
