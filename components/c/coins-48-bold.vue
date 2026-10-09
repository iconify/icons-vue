<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ragurnetf.css';
import '../../css/p/pwh5jrbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ragurnetf"/><path class="pwh5jrbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:coins-48-bold" /></template>
