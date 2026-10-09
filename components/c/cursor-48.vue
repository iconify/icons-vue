<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvzzzkbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nvzzzkbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cursor-48" /></template>
