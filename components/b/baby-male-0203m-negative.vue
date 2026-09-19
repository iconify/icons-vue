<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d85qszb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d85qszb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:baby-male-0203m-negative" /></template>
