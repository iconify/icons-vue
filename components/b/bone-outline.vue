<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcnkfpkbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fcnkfpkbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:bone-outline" /></template>
