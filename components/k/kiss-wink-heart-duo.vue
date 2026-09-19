<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/udfbrio3v.css';
import '../../css/u/uf-kssbkg.css';
import '../../css/w/we8zns5ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="udfbrio3v"/><path class="uf-kssbkg"/><path class="we8zns5ar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:kiss-wink-heart-duo" /></template>
