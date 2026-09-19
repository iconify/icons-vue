<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4kr7db0h.css';
import '../../css/d/d5f9qib4i.css';
import '../../css/o/oc0vi5bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="k4kr7db0h"><path class="d5f9qib4i"/><path class="oc0vi5bvd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:bookmark-off-bold" /></template>
