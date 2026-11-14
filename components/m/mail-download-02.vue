<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/oljd_nblb.css';
import '../../css/d/df-j23bjo.css';
import '../../css/f/ff4ordp-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="oljd_nblb"/><path class="df-j23bjo"/><path class="ff4ordp-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mail-download-02" /></template>
