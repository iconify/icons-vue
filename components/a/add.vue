<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqd8fcboz.css';
import '../../css/p/pg9erg_-c.css';
import '../../css/r/ri_6z2bec.css';
import '../../css/h/hi60_ub5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="hqd8fcboz"><circle class="pg9erg_-c"/><path class="ri_6z2bec"/><path class="hi60_ub5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gala:add" /></template>
