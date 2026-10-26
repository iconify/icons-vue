<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imhg5cbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="imhg5cbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blood-transfusion2x-outline" /></template>
