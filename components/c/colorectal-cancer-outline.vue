<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9y5-zbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s9y5-zbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:colorectal-cancer-outline" /></template>
