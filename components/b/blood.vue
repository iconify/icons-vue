<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/mbsc-1b5r.css';
import '../../css/e/eixrv1bce.css';
import '../../css/o/o3h4-07ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="mbsc-1b5r"/><path class="eixrv1bce"/><path class="o3h4-07ri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:blood" /></template>
