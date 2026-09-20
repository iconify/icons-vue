<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/a/a7kmjvbvt.css';
import '../../css/l/l0yw3t1ep.css';
import '../../css/e/eehirac9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="a7kmjvbvt"/><path class="l0yw3t1ep"/><path class="eehirac9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:episodes" /></template>
