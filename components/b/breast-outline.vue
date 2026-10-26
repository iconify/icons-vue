<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr38e346x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cr38e346x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:breast-outline" /></template>
