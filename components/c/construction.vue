<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7-7u_b9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="z7-7u_b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:construction" /></template>
