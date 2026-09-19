<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-l1pd0_w.css';
import '../../css/a/aghnw_bgv.css';
import '../../css/l/l_1yt4cmi.css';
import '../../css/m/mg82_uzpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h-l1pd0_w"><path clip-rule="evenodd" class="aghnw_bgv"/><path class="l_1yt4cmi"/><path clip-rule="evenodd" class="mg82_uzpj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:flask-solid" /></template>
