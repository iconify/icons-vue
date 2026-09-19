<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_m39d9gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="k_m39d9gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:information-campaign" /></template>
