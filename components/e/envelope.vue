<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kvdw19b_w.css';
import '../../css/i/iaw58s9pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":38,"height":32};
const content = `<g class="cuyn6tgcc"><path class="kvdw19b_w"/><path class="iaw58s9pl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:envelope" /></template>
