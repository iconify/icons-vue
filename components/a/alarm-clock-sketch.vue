<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rop92zbxq.css';
import '../../css/t/t1qtlr2no.css';
import '../../css/f/fo80q9yut.css';
import '../../css/j/jx5032bzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rop92zbxq"/><path class="t1qtlr2no wm-a"/><path class="fo80q9yut wm-k"/><path class="jx5032bzh wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:alarm-clock-sketch" /></template>
