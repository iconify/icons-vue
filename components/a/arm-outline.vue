<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtqv6pbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vtqv6pbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:arm-outline" /></template>
