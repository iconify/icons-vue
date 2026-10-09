<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5slb8bxt.css';
import '../../css/l/lukcxwqgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e5slb8bxt"/><path class="lukcxwqgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crop-48-bold" /></template>
