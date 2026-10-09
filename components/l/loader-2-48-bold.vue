<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbvg1o4cn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tbvg1o4cn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:loader-2-48-bold" /></template>
