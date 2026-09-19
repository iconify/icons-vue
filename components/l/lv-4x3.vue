<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/q/qr9h2yblt.css';
import '../../css/i/ipqs2eb9b.css';
import '../../css/g/gm-qzl1jt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<g class="d2kvgvbvc"><path class="qr9h2yblt"/><path class="ipqs2eb9b"/><path class="gm-qzl1jt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:lv-4x3" /></template>
