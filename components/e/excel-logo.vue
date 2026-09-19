<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0evq45wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d0evq45wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:excel-logo" /></template>
