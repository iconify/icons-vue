<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqcd_1b7g.css';
import '../../css/n/nrssonjct.css';
import '../../css/v/vpcdfbb5g.css';
import '../../css/i/i_fa-oyvq.css';
import '../../css/f/fp6ouy0iq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="cqcd_1b7g"><path class="nrssonjct"/><path class="vpcdfbb5g"/><path class="i_fa-oyvq"/><path class="fp6ouy0iq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:electron-wordmark" /></template>
