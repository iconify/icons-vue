<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa1rnmbzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oa1rnmbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:insurance-48" /></template>
