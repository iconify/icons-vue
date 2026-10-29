<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/imt6p7xdh.css';
import '../../css/a/awlg82ble.css';
import '../../css/c/ck8qjh1op.css';
import '../../css/g/gq0ay1izs.css';
import '../../css/r/rjvsqxvmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="imt6p7xdh wm-k"/><path class="awlg82ble wm-k"/><path class="ck8qjh1op wm-a"/><path class="gq0ay1izs wm-s"/><path class="rjvsqxvmf wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:black-cat-sketch" /></template>
