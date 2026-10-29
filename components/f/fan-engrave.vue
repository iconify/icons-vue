<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/q11d6fe3q.css';
import '../../css/n/n9lwa3bqz.css';
import '../../css/u/uxm70-bnm.css';
import '../../css/b/bpo7kkb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="q11d6fe3q wm-k"/><path class="n9lwa3bqz wm-shadow"/><path class="uxm70-bnm wm-k"/><path class="bpo7kkb-y wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:fan-engrave" /></template>
