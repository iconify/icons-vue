<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tfls_ccga.css';
import '../../css/x/x6y2ap1ue.css';
import '../../css/b/b6u2wybtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tfls_ccga"/><path class="x6y2ap1ue"/><path class="b6u2wybtn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:group" /></template>
