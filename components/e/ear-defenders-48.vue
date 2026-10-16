<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6ezflbgv.css';
import '../../css/r/rx83a-b1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i6ezflbgv"/><path class="rx83a-b1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ear-defenders-48" /></template>
