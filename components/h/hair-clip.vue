<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/h/hyg7__beq.css';
import '../../css/c/c8fcm6b_c.css';
import '../../css/i/inwqb0b3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="hyg7__beq"/><path class="c8fcm6b_c"/><path class="inwqb0b3n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:hair-clip" /></template>
