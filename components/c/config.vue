<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/r/rwpufsici.css';
import '../../css/u/ue4yllbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="rwpufsici"/><path class="ue4yllbit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:config" /></template>
