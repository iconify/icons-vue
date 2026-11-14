<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/u7zizkbrr.css';
import '../../css/d/df-j23bjo.css';
import '../../css/j/jkp3rmbnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u7zizkbrr"/><path class="df-j23bjo"/><path class="jkp3rmbnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mail-reply-02" /></template>
