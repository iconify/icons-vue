<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdsbxfwgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zdsbxfwgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fumarole-48" /></template>
