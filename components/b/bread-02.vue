<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/rt5kw-70y.css';
import '../../css/s/sjz3iqbld.css';
import '../../css/h/hld25s7pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rt5kw-70y"/><path class="sjz3iqbld"/><path class="hld25s7pw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bread-02" /></template>
