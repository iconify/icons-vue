<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8oo7gb6g.css';
import '../../css/u/u7n78m30y.css';
import '../../css/n/ndvxg3usm.css';
import '../../css/r/rl5sxph5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="u7n78m30y"/><path class="ndvxg3usm"/><path class="rl5sxph5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:cloud" /></template>
