<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p860fxb3j.css';
import '../../css/i/igyv2ne6w.css';
import '../../css/o/o3ufdkm0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p860fxb3j"/><path class="igyv2ne6w"/><path class="o3ufdkm0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grid-flexibility-48" /></template>
