<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzn_9vblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dzn_9vblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:kidneys" /></template>
