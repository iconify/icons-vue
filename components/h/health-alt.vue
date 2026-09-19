<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2acizdil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="i2acizdil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:health-alt" /></template>
