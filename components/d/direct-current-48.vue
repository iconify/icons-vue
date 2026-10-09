<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooj-0h2wt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ooj-0h2wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:direct-current-48" /></template>
