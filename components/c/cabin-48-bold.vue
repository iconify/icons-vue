<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_tc1dbfe.css';
import '../../css/i/i1-70q6sv.css';
import '../../css/k/k1qkci9od.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s_tc1dbfe"/><path class="i1-70q6sv"/><path class="k1qkci9od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cabin-48-bold" /></template>
