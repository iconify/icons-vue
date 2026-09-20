<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu7wcxhpc.css';
import '../../css/q/q7cfilbkd.css';
import '../../css/y/ymqozubcz.css';
import '../../css/b/bvmpmfbtm.css';
import '../../css/g/g_hn3zuqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ouiIcon__fillSecondary yu7wcxhpc"/><path class="q7cfilbkd"/><path class="ouiIcon__fillSecondary ymqozubcz"/><path class="bvmpmfbtm"/><path class="g_hn3zuqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-search-profiler" /></template>
