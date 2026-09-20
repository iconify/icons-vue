<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw0xzpbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="iw0xzpbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:dashboard-1-remix" /></template>
