<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcia1ds6l.css';
import '../../css/u/u8ausac2g.css';
import '../../css/x/xufwpsbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pcia1ds6l"/><path class="u8ausac2g"/><path class="xufwpsbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hazard-biohazard-20-bold" /></template>
