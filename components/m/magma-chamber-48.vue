<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5yplhb0m.css';
import '../../css/y/y49f7hyag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e5yplhb0m"/><path class="y49f7hyag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:magma-chamber-48" /></template>
