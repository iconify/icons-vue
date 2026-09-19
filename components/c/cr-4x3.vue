<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv9qcacyl.css';
import '../../css/k/knbkhybae.css';
import '../../css/p/pxs4cphfa.css';
import '../../css/j/jj_owxbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<g class="nv9qcacyl"><path class="knbkhybae"/><path class="pxs4cphfa"/><path class="jj_owxbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:cr-4x3" /></template>
