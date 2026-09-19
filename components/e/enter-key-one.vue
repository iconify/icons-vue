<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/i/ibgn4jeja.css';
import '../../css/i/ica7owv_k.css';
import '../../css/c/cjt33cblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="ibgn4jeja"/><path class="ica7owv_k"/><path class="cjt33cblq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:enter-key-one" /></template>
