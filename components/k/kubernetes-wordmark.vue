<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c846f2b3u.css';
import '../../css/c/c2gy29bva.css';
import '../../css/w/wj_gkq1ud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="c846f2b3u"/><path class="c2gy29bva"/><path class="wj_gkq1ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:kubernetes-wordmark" /></template>
