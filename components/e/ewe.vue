<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnp5fsbrc.css';
import '../../css/s/swb1jq7dp.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/t/t9iazqbwn.css';
import '../../css/m/mbo09cc4c.css';
import '../../css/m/mxpi62-vw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="bnp5fsbrc"/><path class="swb1jq7dp"/><g class="jn8qy4bru"><path class="t9iazqbwn"/><path class="mbo09cc4c"/><path class="mxpi62-vw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:ewe" /></template>
