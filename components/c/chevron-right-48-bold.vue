<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8gtx7ddi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r8gtx7ddi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevron-right-48-bold" /></template>
