<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flffaub2p.css';
import '../../css/h/hryfpbjgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="flffaub2p"/><path class="hryfpbjgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carabiner-48-bold" /></template>
