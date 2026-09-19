<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa6kjeb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fa6kjeb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:boy-0105y" /></template>
