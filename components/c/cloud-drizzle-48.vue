<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rewug1ppt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rewug1ppt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-drizzle-48" /></template>
