<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/t/tv_fp85af.css';
import '../../css/f/f1-3uvb1f.css';
import '../../css/d/djt_l2vuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="tv_fp85af"/><path class="f1-3uvb1f"/><path class="djt_l2vuk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:book-text" /></template>
