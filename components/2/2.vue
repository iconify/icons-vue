<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylf8t4bhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ylf8t4bhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:2" /></template>
