<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kijk4bcxn.css';
import '../../css/n/nuxk96b5j.css';
import '../../css/a/agevo0b7q.css';
import '../../css/x/xej4-bcnx.css';
import '../../css/x/xe40m6lqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kijk4bcxn"/><path class="nuxk96b5j wm-k"/><path class="agevo0b7q wm-k"/><path class="wm-k xej4-bcnx"/><path class="wm-a xe40m6lqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:graduation-cap-sketch" /></template>
