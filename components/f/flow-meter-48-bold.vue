<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_6rrccmc.css';
import '../../css/u/ufby2lc1j.css';
import '../../css/x/x-xho5uub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m_6rrccmc"/><path class="ufby2lc1j"/><path class="x-xho5uub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flow-meter-48-bold" /></template>
