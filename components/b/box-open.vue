<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/u/ubczdxbzu.css';
import '../../css/v/v5zmisb0l.css';
import '../../css/k/k73vt3bvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="ubczdxbzu"/><path class="v5zmisb0l"/><path class="k73vt3bvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:box-open" /></template>
