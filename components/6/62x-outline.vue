<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0mi_2b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="t0mi_2b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:62x-outline" /></template>
