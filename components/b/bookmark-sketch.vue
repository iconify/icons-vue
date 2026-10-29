<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/z3gwnvuvk.css';
import '../../css/r/ra0fx1pwm.css';
import '../../css/m/mccgqq6yq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="z3gwnvuvk"/><path class="ra0fx1pwm"/><path class="mccgqq6yq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bookmark-sketch" /></template>
