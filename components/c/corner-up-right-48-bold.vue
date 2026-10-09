<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2hr5sbai.css';
import '../../css/y/yvjkteb0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y2hr5sbai"/><path class="yvjkteb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-up-right-48-bold" /></template>
