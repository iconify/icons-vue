<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9taiwyhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="e9taiwyhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:basic-motorcycle-outline" /></template>
