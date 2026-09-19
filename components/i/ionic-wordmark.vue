<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thpy47d_f.css';
import '../../css/l/lwha5_b5g.css';
import '../../css/q/qm9invowl.css';
import '../../css/r/rm1klhb5f.css';
import '../../css/w/wb4efo_qd.css';
import '../../css/e/ecf5uvhjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="thpy47d_f"><path class="lwha5_b5g"/><circle class="qm9invowl"/><circle class="rm1klhb5f"/><circle class="wb4efo_qd"/><path class="ecf5uvhjg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:ionic-wordmark" /></template>
