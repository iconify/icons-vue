<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/q/qs-agmjdy.css';
import '../../css/c/cs3t1qbvt.css';
import '../../css/m/mmjpv4bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="qs-agmjdy"/><path class="cs3t1qbvt"/><path class="mmjpv4bpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:fruits" /></template>
