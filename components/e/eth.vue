<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/d/dbmfimb0q.css';
import '../../css/l/l5y23ru5w.css';
import '../../css/a/axu8vacgl.css';
import '../../css/k/kouxvgbln.css';
import '../../css/g/gzzcnbppf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="n1lsf0bnc"><path class="dbmfimb0q"/><g class="l5y23ru5w"><path class="axu8vacgl"/><path class="kouxvgbln"/><path class="gzzcnbppf"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:eth" /></template>
