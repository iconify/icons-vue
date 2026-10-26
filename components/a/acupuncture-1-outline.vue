<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyctcdb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xyctcdb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:acupuncture-1-outline" /></template>
