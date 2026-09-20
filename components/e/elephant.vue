<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idyt3mb2g.css';
import '../../css/m/m_grtzbhg.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/d/dh9ai_bnx.css';
import '../../css/h/hkw9obv5y.css';
import '../../css/u/u1cbtpvhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="idyt3mb2g"/><path class="m_grtzbhg"/><g class="jn8qy4bru"><path class="dh9ai_bnx"/><path class="hkw9obv5y"/><path class="u1cbtpvhw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:elephant" /></template>
