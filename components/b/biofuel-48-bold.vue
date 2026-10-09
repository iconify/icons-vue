<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khd4an8mp.css';
import '../../css/d/dqca1ac-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="khd4an8mp"/><path class="dqca1ac-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:biofuel-48-bold" /></template>
