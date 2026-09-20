<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4u8pbwjc.css';
import '../../css/i/i9lmwgbsb.css';
import '../../css/r/rnbjb7b6u.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/f/f1hodz7-e.css';
import '../../css/e/e9evbnnhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<g class="x4u8pbwjc"><path class="i9lmwgbsb"/><path class="rnbjb7b6u"/></g><g class="jn8qy4bru"><path class="f1hodz7-e"/><path class="e9evbnnhw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:leg" /></template>
