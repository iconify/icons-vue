<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/hy85st8ir.css';
import '../../css/j/jfrelvtns.css';
import '../../css/u/u9b1crbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="hy85st8ir"/><path class="jfrelvtns"/><path class="u9b1crbyt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cap-projecting" /></template>
