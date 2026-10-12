<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtgmy3b7z.css';
import '../../css/h/hodl4aclm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qtgmy3b7z"/><path class="hodl4aclm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gps-48-bold" /></template>
