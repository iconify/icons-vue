<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6d4icc2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x6d4icc2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:circle-large2x-outline" /></template>
