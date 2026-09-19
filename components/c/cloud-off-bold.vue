<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4kr7db0h.css';
import '../../css/m/mr69ebfaw.css';
import '../../css/o/oc0vi5bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="k4kr7db0h"><path class="mr69ebfaw"/><path class="oc0vi5bvd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:cloud-off-bold" /></template>
