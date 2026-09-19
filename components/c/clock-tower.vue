<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mi5jvd-ss.css';
import '../../css/m/m_5a5dbtz.css';
import '../../css/p/pi5e1_bfv.css';
import '../../css/y/yqw3pssfo.css';
import '../../css/s/sw_hpqb_i.css';
import '../../css/f/fhkc_wc2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="mi5jvd-ss"/><path class="m_5a5dbtz"/><path class="pi5e1_bfv"/><rect class="yqw3pssfo"/><circle class="sw_hpqb_i"/><path class="fhkc_wc2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:clock-tower" /></template>
