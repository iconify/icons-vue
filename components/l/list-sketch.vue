<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/n1es_rwco.css';
import '../../css/z/zso6h7bac.css';
import '../../css/a/a5_my2x1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="n1es_rwco wm-k"/><path class="wm-k zso6h7bac"/><path class="a5_my2x1o wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-sketch" /></template>
