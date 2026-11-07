<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fyr67fbfm.css';
import '../../css/e/e_wor2bbs.css';
import '../../css/l/lm7otu1mj.css';
import '../../css/b/bu-wc30dp.css';
import '../../css/g/gvinp5b1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fyr67fbfm"/><path class="e_wor2bbs"/><path class="lm7otu1mj"/><path class="bu-wc30dp"/><path class="gvinp5b1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flash-drive-broken" /></template>
