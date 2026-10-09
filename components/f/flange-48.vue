<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2g9qy8wl.css';
import '../../css/c/cn-h_ztnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f2g9qy8wl"/><path class="cn-h_ztnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flange-48" /></template>
