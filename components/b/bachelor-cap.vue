<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/j/jb6j1ybag.css';
import '../../css/b/bk3dgpqfa.css';
import '../../css/d/dtzqdk4dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="jb6j1ybag"/><path class="bk3dgpqfa"/><path class="dtzqdk4dw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:bachelor-cap" /></template>
