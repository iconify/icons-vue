<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mml-20uch.css';
import '../../css/e/e80us0jnl.css';
import '../../css/t/t9qlqybcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mml-20uch"/><path class="e80us0jnl"/><path class="t9qlqybcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ferris-wheel-48" /></template>
