<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8h1-6bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="q8h1-6bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:foot" /></template>
