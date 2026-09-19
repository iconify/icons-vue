<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7srihbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="m7srihbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:f2x-outline" /></template>
