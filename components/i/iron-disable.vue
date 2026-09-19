<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/l/ln41zjkly.css';
import '../../css/f/f6c0wnbzz.css';
import '../../css/i/igx57ccmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="ln41zjkly"/><circle class="f6c0wnbzz"/><path class="igx57ccmj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:iron-disable" /></template>
