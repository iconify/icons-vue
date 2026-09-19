<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we6_thbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="we6_thbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:heartbeat" /></template>
