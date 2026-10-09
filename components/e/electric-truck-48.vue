<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xujk5fdpi.css';
import '../../css/e/e5asi9aud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xujk5fdpi"/><path class="e5asi9aud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-truck-48" /></template>
