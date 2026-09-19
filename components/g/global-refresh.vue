<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/ffrak0b0s.css';
import '../../css/n/nqrwakdsg.css';
import '../../css/q/qg4l4xbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ffrak0b0s"/><path class="nqrwakdsg"/><path class="qg4l4xbso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:global-refresh" /></template>
