<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sebac8bfa.css';
import '../../css/p/pgjsmy3yc.css';
import '../../css/q/qfzblfw3y.css';
import '../../css/i/i_e0aq0rj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sebac8bfa"/><path class="pgjsmy3yc wm-a"/><path class="qfzblfw3y wm-k"/><path class="i_e0aq0rj wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:archive-restore-sketch" /></template>
