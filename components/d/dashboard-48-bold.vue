<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw_1otbkh.css';
import '../../css/e/ed7w77b1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rw_1otbkh"/><path class="ed7w77b1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dashboard-48-bold" /></template>
