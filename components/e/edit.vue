<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/m/mk263c2vx.css';
import '../../css/y/yetgw9b4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="n1lsf0bnc"><path class="mk263c2vx"/><path class="yetgw9b4w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:edit" /></template>
