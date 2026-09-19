<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/vvodlpb0u.css';
import '../../css/x/xotln27_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="n1lsf0bnc"><path class="vvodlpb0u"/><path class="xotln27_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:logo-tracktion" /></template>
