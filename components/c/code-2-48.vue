<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkcr5wbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nkcr5wbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:code-2-48" /></template>
