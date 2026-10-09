<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdj4_lhpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zdj4_lhpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevron-up-48-bold" /></template>
