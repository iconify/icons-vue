<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh809gb4r.css';
import '../../css/p/pahc4sbmv.css';
import '../../css/y/yvkfxeizw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zh809gb4r"/><path class="pahc4sbmv"/><path class="yvkfxeizw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:home-48-bold" /></template>
