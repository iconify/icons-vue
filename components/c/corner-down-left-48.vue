<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w64l-ub0s.css';
import '../../css/f/f8bjlbjhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w64l-ub0s"/><path class="f8bjlbjhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-down-left-48" /></template>
