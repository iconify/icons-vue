<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/koxstha1f.css';
import '../../css/v/vpp78ggra.css';
import '../../css/w/w2y3zvo5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="koxstha1f"/><path class="vpp78ggra"/><path class="w2y3zvo5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:emulatorjs" /></template>
