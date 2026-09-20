<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xck5rbc3z.css';
import '../../css/u/u9l0xvbmx.css';
import '../../css/j/ji-4p20pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="xck5rbc3z"><path class="u9l0xvbmx"/><path class="ji-4p20pf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:hourglass" /></template>
