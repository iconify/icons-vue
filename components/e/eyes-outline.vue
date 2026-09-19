<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xstbx_bdq.css';
import '../../css/q/q-pec5bsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="xstbx_bdq"/><path clip-rule="evenodd" class="q-pec5bsd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:eyes-outline" /></template>
