<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/m-ge5cbxd.css';
import '../../css/y/y_m0nh94x.css';
import '../../css/m/m8c-n29ae.css';
import '../../css/h/h8mapob3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="m-ge5cbxd wm-k"/><path class="wm-a y_m0nh94x"/><path class="m8c-n29ae wm-k"/><path class="h8mapob3k wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:dna-sketch" /></template>
