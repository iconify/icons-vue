<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q17vvwwce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="q17vvwwce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:credit-card" /></template>
