<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvev64bnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="uvev64bnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:construction2x-outline" /></template>
