<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah3zxz6rp.css';
import '../../css/h/h_kmv8b8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ah3zxz6rp"/><path class="h_kmv8b8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chain-48" /></template>
