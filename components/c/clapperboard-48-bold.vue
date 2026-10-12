<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7c_5vb9e.css';
import '../../css/m/mqkco8bnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s7c_5vb9e"/><path class="mqkco8bnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clapperboard-48-bold" /></template>
