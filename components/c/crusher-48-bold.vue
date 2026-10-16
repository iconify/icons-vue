<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd0ibrbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pd0ibrbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crusher-48-bold" /></template>
