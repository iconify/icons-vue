<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el1pu6btt.css';
import '../../css/d/d4ndp2pgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="el1pu6btt"/><path class="d4ndp2pgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cactus-48" /></template>
