<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/goie45bfg.css';
import '../../css/q/q87m_jinq.css';
import '../../css/o/oqrsy3bng.css';
import '../../css/c/c47hojbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="goie45bfg"/><path class="q87m_jinq"/><path class="oqrsy3bng"/><path class="c47hojbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-x-48-bold" /></template>
