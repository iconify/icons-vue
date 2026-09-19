<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz7dlcc-l.css';
import '../../css/d/dhqx3vboc.css';
import '../../css/b/b87hwbboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="tz7dlcc-l"><path class="dhqx3vboc"/><path class="b87hwbboa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:javascript" /></template>
