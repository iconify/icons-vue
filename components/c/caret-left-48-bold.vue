<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py4tycbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="py4tycbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caret-left-48-bold" /></template>
