<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiecv_t_z.css';
import '../../css/w/wryrt8b-k.css';
import '../../css/c/cm6td6aoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aiecv_t_z"/><path class="wryrt8b-k"/><path class="cm6td6aoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fire-engine-48-bold" /></template>
