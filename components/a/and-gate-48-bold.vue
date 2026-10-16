<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7zl_d3jf.css';
import '../../css/p/p7-m9i8me.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d7zl_d3jf"/><path class="p7-m9i8me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:and-gate-48-bold" /></template>
