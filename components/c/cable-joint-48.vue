<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbc6c5bqk.css';
import '../../css/x/xy_8owk3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nbc6c5bqk"/><path class="xy_8owk3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cable-joint-48" /></template>
