<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sc7vf9bsj.css';
import '../../css/o/oh6yrebxg.css';
import '../../css/q/qbjvmhoys.css';
import '../../css/s/svm9pnbzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sc7vf9bsj"/><path class="oh6yrebxg wm-a"/><path class="qbjvmhoys wm-k"/><path class="svm9pnbzs wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-warning-sketch" /></template>
