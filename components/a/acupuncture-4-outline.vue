<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccjkfxb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ccjkfxb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:acupuncture-4-outline" /></template>
