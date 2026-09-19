<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apb9iiktg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="apb9iiktg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:dialysis" /></template>
