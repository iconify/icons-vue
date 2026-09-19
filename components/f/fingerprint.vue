<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h919i69mc.css';
import '../../css/a/aosxdz-mw.css';
import '../../css/e/eqjj6acuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="h919i69mc"/><path class="aosxdz-mw"/><path class="eqjj6acuc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:fingerprint" /></template>
