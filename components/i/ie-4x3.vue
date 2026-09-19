<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv9qcacyl.css';
import '../../css/y/y5vgbcb_s.css';
import '../../css/b/bpmvr7beb.css';
import '../../css/p/pf5aoggpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<g class="nv9qcacyl"><path class="y5vgbcb_s"/><path class="bpmvr7beb"/><path class="pf5aoggpl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:ie-4x3" /></template>
