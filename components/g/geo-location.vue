<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlv7khici.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xlv7khici"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:geo-location" /></template>
