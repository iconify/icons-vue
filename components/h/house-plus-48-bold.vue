<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/goie45bfg.css';
import '../../css/q/q87m_jinq.css';
import '../../css/i/it04kcbvr.css';
import '../../css/f/fdlxrep5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="goie45bfg"/><path class="q87m_jinq"/><path class="it04kcbvr"/><path class="fdlxrep5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-plus-48-bold" /></template>
