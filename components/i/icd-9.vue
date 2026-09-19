<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwv2nnc9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="iwv2nnc9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:icd-9" /></template>
