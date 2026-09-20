<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9pq-abme.css';
import '../../css/i/i9lmwgbsb.css';
import '../../css/c/cxyg_zbqp.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/f/f1hodz7-e.css';
import '../../css/e/e9evbnnhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<g class="k9pq-abme"><path class="i9lmwgbsb"/><path class="cxyg_zbqp"/></g><g class="jn8qy4bru"><path class="f1hodz7-e"/><path class="e9evbnnhw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:leg-medium-skin-tone" /></template>
