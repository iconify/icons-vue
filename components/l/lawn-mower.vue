<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8oo7gb6g.css';
import '../../css/h/h8qj45bdj.css';
import '../../css/s/spwb3dbss.css';
import '../../css/j/jup7mqu6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="h8qj45bdj"/><path class="spwb3dbss"/><path class="jup7mqu6s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:lawn-mower" /></template>
