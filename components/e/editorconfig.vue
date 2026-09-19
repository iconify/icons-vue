<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy1cqobue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gy1cqobue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:editorconfig" /></template>
