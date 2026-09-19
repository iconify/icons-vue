<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm8vpmbuj.css';
import '../../css/y/y0l3i_qwp.css';
import '../../css/m/mxgov2bur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bm8vpmbuj"/><path class="y0l3i_qwp"/><circle class="mxgov2bur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:cable-release" /></template>
