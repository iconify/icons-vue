<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/m/mf1qfwb3p.css';
import '../../css/c/c3ra92qkt.css';
import '../../css/q/qvpu09b-s.css';
import '../../css/r/ru3w0x1yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mf1qfwb3p"/><path class="c3ra92qkt"/><path class="qvpu09b-s"/><path class="ru3w0x1yt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:charging-session" /></template>
