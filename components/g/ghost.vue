<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/c/cw-iw1_ie.css';
import '../../css/i/im6flx-ax.css';
import '../../css/z/z-phgabtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="cw-iw1_ie"/><path class="im6flx-ax"/><path class="z-phgabtr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:ghost" /></template>
