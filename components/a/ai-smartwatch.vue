<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/a/am_u226-o.css';
import '../../css/x/xn8jdabvx.css';
import '../../css/l/lpx543bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="am_u226-o"/><path class="xn8jdabvx"/><path class="lpx543bxg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-smartwatch" /></template>
