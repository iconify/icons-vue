<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqf5v4byj.css';
import '../../css/j/jna5_7bho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wqf5v4byj"/><path class="jna5_7bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:conveyor-48-bold" /></template>
