<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/z/z2z8s690m.css';
import '../../css/d/dlenz_bwo.css';
import '../../css/s/stb41lb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="z2z8s690m"/><path class="dlenz_bwo"/><path class="stb41lb3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:harm" /></template>
