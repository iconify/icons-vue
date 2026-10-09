<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysmjyxbxr.css';
import '../../css/a/a3h2qmbcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ysmjyxbxr"/><path class="a3h2qmbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dam-48-bold" /></template>
