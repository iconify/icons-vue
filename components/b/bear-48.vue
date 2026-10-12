<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7d8ty_6p.css';
import '../../css/e/e8_qdzh7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l7d8ty_6p"/><path class="e8_qdzh7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bear-48" /></template>
