<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/e/em1eecbma.css';
import '../../css/k/ke0058byd.css';
import '../../css/l/l76rhnbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="em1eecbma"/><path class="ke0058byd"/><path class="l76rhnbaq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:fingerprint" /></template>
