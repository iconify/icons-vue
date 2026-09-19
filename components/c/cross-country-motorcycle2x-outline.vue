<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl1hntrbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cl1hntrbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:cross-country-motorcycle2x-outline" /></template>
