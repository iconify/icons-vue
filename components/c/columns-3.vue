<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/g/gvys7u6cq.css';
import '../../css/x/xasz54-bm.css';
import '../../css/k/kjkbr1xrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="gvys7u6cq"/><path class="xasz54-bm"/><path class="kjkbr1xrf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:columns-3" /></template>
