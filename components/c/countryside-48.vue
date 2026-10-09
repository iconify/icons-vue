<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_c1rlbdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q_c1rlbdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:countryside-48" /></template>
