<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9o2spbcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f9o2spbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:02x-outline" /></template>
