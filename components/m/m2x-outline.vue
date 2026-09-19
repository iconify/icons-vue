<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb61mvb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="eb61mvb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:m2x-outline" /></template>
