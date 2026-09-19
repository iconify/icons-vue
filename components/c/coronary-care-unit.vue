<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4u0dd6fq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="y4u0dd6fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:coronary-care-unit" /></template>
