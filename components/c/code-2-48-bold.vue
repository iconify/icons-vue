<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvvq2qbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gvvq2qbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:code-2-48-bold" /></template>
