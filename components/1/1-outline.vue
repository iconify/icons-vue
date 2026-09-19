<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgemc-b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xgemc-b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:1-outline" /></template>
