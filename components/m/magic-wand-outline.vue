<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sve_pcibh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sve_pcibh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:magic-wand-outline" /></template>
