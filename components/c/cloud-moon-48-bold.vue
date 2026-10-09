<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwy0au9lc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hwy0au9lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-moon-48-bold" /></template>
