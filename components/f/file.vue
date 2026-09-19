<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o31z5xgnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o31z5xgnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:file" /></template>
