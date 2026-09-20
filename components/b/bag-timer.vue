<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7fmnlb4r.css';
import '../../css/r/r1iwxwpgc.css';
import '../../css/f/fh_8iqr2b.css';
import '../../css/q/qpdv9achi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path class="r1iwxwpgc"/><path class="fh_8iqr2b"/><path class="qpdv9achi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bag-timer" /></template>
