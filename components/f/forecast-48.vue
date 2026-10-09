<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv4k_bcjk.css';
import '../../css/o/oolbpf3kw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dv4k_bcjk"/><path class="oolbpf3kw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:forecast-48" /></template>
