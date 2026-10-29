<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/oua51pdjw.css';
import '../../css/n/nncr0gjwr.css';
import '../../css/h/h3f-tbb6j.css';
import '../../css/v/vy9khb81y.css';
import '../../css/c/cwe0l_ktm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="oua51pdjw"/><path class="nncr0gjwr wm-s"/><path class="h3f-tbb6j wm-k"/><path class="vy9khb81y wm-a"/><path class="cwe0l_ktm wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:heater-sketch" /></template>
