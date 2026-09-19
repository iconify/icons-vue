<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/u/ukr1ucczm.css';
import '../../css/s/s7z8uvbmf.css';
import '../../css/j/jddlfcbxw.css';
import '../../css/q/qjgr22b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><circle class="ukr1ucczm"/><circle class="s7z8uvbmf"/><path class="jddlfcbxw"/><path class="qjgr22b3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:camera-five" /></template>
