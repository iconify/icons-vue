<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8yv5ybdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="z8yv5ybdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:health-data-security" /></template>
