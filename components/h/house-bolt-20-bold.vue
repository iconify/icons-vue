<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coivkzecr.css';
import '../../css/e/ed9sx_fzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="coivkzecr"/><path class="ed9sx_fzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-bolt-20-bold" /></template>
