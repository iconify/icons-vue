<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fmg5-rbfu.css';
import '../../css/v/vgynvrhex.css';
import '../../css/g/g_eh3ebdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fmg5-rbfu"/><path class="vgynvrhex"/><path class="g_eh3ebdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:logout-3-linear" /></template>
