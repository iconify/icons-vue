<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_e3wgwgv.css';
import '../../css/t/tgihwabmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l_e3wgwgv"/><path class="tgihwabmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bridge-48" /></template>
