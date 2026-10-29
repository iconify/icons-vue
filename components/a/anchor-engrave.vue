<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/s9cu-m2zc.css';
import '../../css/a/a2w082jqj.css';
import '../../css/v/v44qq45nj.css';
import '../../css/p/ploa71bki.css';
import '../../css/n/n3rsbi38y.css';
import '../../css/u/u2f_ne4qg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="s9cu-m2zc wm-k"/><path class="a2w082jqj wm-a"/><path class="v44qq45nj wm-shadow"/><path class="ploa71bki wm-a"/><path class="n3rsbi38y wm-k"/><path class="u2f_ne4qg wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:anchor-engrave" /></template>
