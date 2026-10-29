<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v65z5be8c.css';
import '../../css/o/o19bcrb8v.css';
import '../../css/d/d87ng64hw.css';
import '../../css/e/exthxrocb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v65z5be8c"/><path class="o19bcrb8v wm-a"/><path class="d87ng64hw wm-k"/><path class="exthxrocb wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:folder-check-sketch" /></template>
