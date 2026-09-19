<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l__rt35cm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="l__rt35cm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:discriminating-concentration-bioassays-outline" /></template>
