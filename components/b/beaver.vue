<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibafe3iko.css';
import '../../css/h/h02blnj9b.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/u/u0cmkeodx.css';
import '../../css/e/erv6rqbpa.css';
import '../../css/u/ub-aomhiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ibafe3iko"/><path class="h02blnj9b"/><g class="jn8qy4bru"><path class="u0cmkeodx"/><path class="erv6rqbpa"/><path class="ub-aomhiq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:beaver" /></template>
