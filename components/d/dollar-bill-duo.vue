<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zk0wjn-dd.css';
import '../../css/y/yn8mhpbye.css';
import '../../css/p/p0qy-sbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="zk0wjn-dd"/><path class="yn8mhpbye"/><path class="p0qy-sbma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:dollar-bill-duo" /></template>
