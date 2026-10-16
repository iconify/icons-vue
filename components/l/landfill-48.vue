<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elj7bpqnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="elj7bpqnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:landfill-48" /></template>
