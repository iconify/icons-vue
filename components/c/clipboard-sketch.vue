<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lyz3fuknv.css';
import '../../css/z/zh7yrubjw.css';
import '../../css/c/cdnvyfk7r.css';
import '../../css/k/k8brllbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lyz3fuknv"/><path class="wm-k zh7yrubjw"/><path class="cdnvyfk7r wm-k"/><path class="k8brllbsz wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:clipboard-sketch" /></template>
