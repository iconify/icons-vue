<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok65zv8cj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ok65zv8cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:bookmark-check-20-solid" /></template>
