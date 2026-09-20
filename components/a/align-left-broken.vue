<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hb2atdblt.css';
import '../../css/o/oh-ffpj9g.css';
import '../../css/o/ou2j_7qjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hb2atdblt"/><path class="oh-ffpj9g"/><path class="ou2j_7qjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-left-broken" /></template>
