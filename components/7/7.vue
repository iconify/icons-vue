<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljq432_5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ljq432_5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:7" /></template>
