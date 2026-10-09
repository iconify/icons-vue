<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mheydraer.css';
import '../../css/v/vrwv3ubdj.css';
import '../../css/l/lheu_vbwv.css';
import '../../css/t/tq_15om_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mheydraer"/><path class="vrwv3ubdj"/><path class="lheu_vbwv"/><path class="tq_15om_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gravity-storage-48-bold" /></template>
