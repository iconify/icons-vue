<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jspej-bbf.css';
import '../../css/n/npf4dcx9x.css';
import '../../css/k/kdvp9-2dd.css';
import '../../css/e/ezbn6olzb.css';
import '../../css/q/qc29-dbwu.css';
import '../../css/z/z0hg7qbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="jspej-bbf"/><path class="npf4dcx9x"/><path clip-rule="evenodd" class="kdvp9-2dd"/><path class="ezbn6olzb"/><path class="qc29-dbwu"/><path clip-rule="evenodd" class="z0hg7qbpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:cv-print" /></template>
