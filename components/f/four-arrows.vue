<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/u/uj5tubcvw.css';
import '../../css/j/jb5_c0nah.css';
import '../../css/q/qsirhpcjy.css';
import '../../css/u/uce_dv5xt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="uj5tubcvw"/><path class="jb5_c0nah"/><path class="qsirhpcjy"/><path class="uce_dv5xt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:four-arrows" /></template>
