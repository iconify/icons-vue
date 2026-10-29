<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/s/sdo3s5gsn.css';
import '../../css/g/g91qa5pir.css';
import '../../css/m/mx2e90gcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="sdo3s5gsn"/><path class="g91qa5pir wm-a"/><path class="mx2e90gcg wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:briefcase-business-solid" /></template>
