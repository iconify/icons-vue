<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqnm1rstj.css';
import '../../css/p/pmzrqcc7c.css';
import '../../css/b/bv8dp0iic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yqnm1rstj"/><path class="pmzrqcc7c"/><path class="bv8dp0iic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:butterfly-valve-48-bold" /></template>
