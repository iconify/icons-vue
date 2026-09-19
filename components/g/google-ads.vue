<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/f/fw4qprb3o.css';
import '../../css/f/fd-er-bup.css';
import '../../css/j/j160kwbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="fw4qprb3o"/><path class="fd-er-bup"/><circle transform="rotate(25 12.083 36.688)" class="j160kwbfi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:google-ads" /></template>
