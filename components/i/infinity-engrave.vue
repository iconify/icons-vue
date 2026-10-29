<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jd9mkhbdr.css';
import '../../css/o/omerkobbu.css';
import '../../css/t/tef1dsoih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jd9mkhbdr"/><path class="omerkobbu wm-shadow"/><path class="tef1dsoih"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:infinity-engrave" /></template>
