<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y--jnj11k.css';
import '../../css/k/kqp7h7bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y--jnj11k"/><path class="kqp7h7bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-scatter-48-bold" /></template>
