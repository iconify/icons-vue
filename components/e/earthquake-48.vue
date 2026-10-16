<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piiyerbma.css';
import '../../css/s/su0p68bml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="piiyerbma"/><path class="su0p68bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:earthquake-48" /></template>
