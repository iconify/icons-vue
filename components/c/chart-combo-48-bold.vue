<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghe6iqpty.css';
import '../../css/e/ez7xqcrkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ghe6iqpty"/><path class="ez7xqcrkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-combo-48-bold" /></template>
