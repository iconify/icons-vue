<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5e0utiaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f5e0utiaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ear-outline" /></template>
