<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_raf5bng.css';
import '../../css/i/i9lmwgbsb.css';
import '../../css/p/pn4la1n1m.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/f/f1hodz7-e.css';
import '../../css/e/e9evbnnhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<g class="e_raf5bng"><path class="i9lmwgbsb"/><path class="pn4la1n1m"/></g><g class="jn8qy4bru"><path class="f1hodz7-e"/><path class="e9evbnnhw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:leg-dark-skin-tone" /></template>
