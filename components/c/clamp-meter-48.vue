<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muwzxbc8x.css';
import '../../css/o/okfg1bcol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="muwzxbc8x"/><path class="okfg1bcol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clamp-meter-48" /></template>
