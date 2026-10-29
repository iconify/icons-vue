<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nof7gjbxm.css';
import '../../css/y/yz3ko5bsq.css';
import '../../css/i/itk1anblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nof7gjbxm"/><path class="wm-k yz3ko5bsq"/><path class="itk1anblx wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:banknote-sketch" /></template>
