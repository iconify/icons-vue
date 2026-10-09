<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk0rhabac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tk0rhabac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caret-down-48-bold" /></template>
