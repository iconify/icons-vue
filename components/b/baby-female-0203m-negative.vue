<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it6b2upls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="it6b2upls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:baby-female-0203m-negative" /></template>
