<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/b/bmvtfmy4l.css';
import '../../css/z/zut5arb6z.css';
import '../../css/w/wuim45b6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="bmvtfmy4l"/><path class="zut5arb6z"/><path class="wuim45b6m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:doctor-01" /></template>
