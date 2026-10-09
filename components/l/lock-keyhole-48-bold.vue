<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm6x03w9o.css';
import '../../css/q/q5_nrjb0f.css';
import '../../css/m/mlj68nbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lm6x03w9o"/><path class="q5_nrjb0f"/><path class="mlj68nbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lock-keyhole-48-bold" /></template>
