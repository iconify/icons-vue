<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b74xzvbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b74xzvbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:gastroenterology-outline" /></template>
