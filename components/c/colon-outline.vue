<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecu0gbbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ecu0gbbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:colon-outline" /></template>
