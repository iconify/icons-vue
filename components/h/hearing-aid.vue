<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csiavtr3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="csiavtr3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:hearing-aid" /></template>
