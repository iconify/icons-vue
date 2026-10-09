<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb9x9-c_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mb9x9-c_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-48" /></template>
