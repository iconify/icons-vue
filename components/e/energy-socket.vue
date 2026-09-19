<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/d/dc3vmxbte.css';
import '../../css/c/c0yckqbit.css';
import '../../css/i/iaiylo83l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="dc3vmxbte"/><path class="c0yckqbit"/><path class="iaiylo83l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:energy-socket" /></template>
