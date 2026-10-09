<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xedufpf4g.css';
import '../../css/p/pfnbi-dgu.css';
import '../../css/r/rnwwcable.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xedufpf4g"/><path class="pfnbi-dgu"/><path class="rnwwcable"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-trading-48" /></template>
