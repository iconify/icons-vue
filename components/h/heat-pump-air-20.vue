<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw2cq1b_w.css';
import '../../css/g/g754atbee.css';
import '../../css/r/r1difiu_d.css';
import '../../css/j/j8rue7bvc.css';
import '../../css/h/hnm4jlbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iw2cq1b_w"/><path class="g754atbee"/><path class="r1difiu_d"/><path class="j8rue7bvc"/><path class="hnm4jlbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-pump-air-20" /></template>
