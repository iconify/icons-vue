<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu7nbqy7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lu7nbqy7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:copy-check-light" /></template>
