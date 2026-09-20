<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iib_u5vix.css';
import '../../css/e/espirmbhi.css';
import '../../css/o/ogrg-o-wi.css';
import '../../css/s/s_5ru8bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGWCs6ObpT" class="iib_u5vix"/></defs><use href="#SVGWCs6ObpT"/><use href="#SVGWCs6ObpT"/><path clip-rule="evenodd" class="espirmbhi"/><path class="ogrg-o-wi"/><path clip-rule="evenodd" class="s_5ru8bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lcs" /></template>
