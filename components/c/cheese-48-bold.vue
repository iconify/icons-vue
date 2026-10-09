<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4kzwwbha.css';
import '../../css/n/n5_c-mepp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e4kzwwbha"/><path class="n5_c-mepp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cheese-48-bold" /></template>
