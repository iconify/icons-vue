<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2v2x5blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i2v2x5blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:guide-dog" /></template>
