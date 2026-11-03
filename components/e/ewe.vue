<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnp5fsbrc.css';
import '../../css/s/swb1jq7dp.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/c/cpr9xye3j.css';
import '../../css/r/r71gmxmqy.css';
import '../../css/m/mxpi62-vw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="bnp5fsbrc"/><path class="swb1jq7dp"/><g class="jn8qy4bru"><path class="cpr9xye3j"/><path class="r71gmxmqy"/><path class="mxpi62-vw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:ewe" /></template>
