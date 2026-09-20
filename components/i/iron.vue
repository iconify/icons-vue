<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8oo7gb6g.css';
import '../../css/o/osh0h0p7g.css';
import '../../css/o/ocdk10b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="osh0h0p7g"/><path class="ocdk10b8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:iron" /></template>
