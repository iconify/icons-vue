<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya_ke-i5o.css';
import '../../css/v/vliuxwelf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ya_ke-i5o"/><path class="vliuxwelf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:junction-box-48" /></template>
