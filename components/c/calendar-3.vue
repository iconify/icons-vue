<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/l/lx6sfha5x.css';
import '../../css/q/qz0s-uf3y.css';
import '../../css/b/bukhfnboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<g class="bi12bsetm"><path class="lx6sfha5x"/><path class="qz0s-uf3y"/><path class="bukhfnboa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:calendar-3" /></template>
