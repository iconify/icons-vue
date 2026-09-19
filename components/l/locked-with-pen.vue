<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rkcn1o1ue.css';
import '../../css/s/scxuwubey.css';
import '../../css/t/t0r3qrbre.css';
import '../../css/t/tnlf20boh.css';
import '../../css/y/yxosflbcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="rkcn1o1ue"/><path class="scxuwubey"/><path class="t0r3qrbre"/><path class="tnlf20boh"/><path class="yxosflbcv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:locked-with-pen" /></template>
