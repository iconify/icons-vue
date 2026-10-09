<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzr7ecx0m.css';
import '../../css/l/lizp2ibyj.css';
import '../../css/v/vph4g2brq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mzr7ecx0m"/><path class="lizp2ibyj"/><path class="vph4g2brq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cogs-48-bold" /></template>
