<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3ypzo5fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3ypzo5fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:auto-hold-fill" /></template>
