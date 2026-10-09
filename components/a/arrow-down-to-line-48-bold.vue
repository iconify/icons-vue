<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j50zvhxpr.css';
import '../../css/e/ey0nx0bof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j50zvhxpr"/><path class="ey0nx0bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-down-to-line-48-bold" /></template>
