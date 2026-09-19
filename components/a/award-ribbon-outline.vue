<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj5b0nhsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="uj5b0nhsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:award-ribbon-outline" /></template>
