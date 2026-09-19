<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/x/xhdah4bbl.css';
import '../../css/a/am1igebwo.css';
import '../../css/c/c5dwnijuu.css';
import '../../css/e/e3l3qbcgf.css';
import '../../css/e/eaezi2ufu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="xhdah4bbl"/><path class="am1igebwo"/><path class="c5dwnijuu"/><path class="e3l3qbcgf"/><path class="eaezi2ufu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:expand-up" /></template>
