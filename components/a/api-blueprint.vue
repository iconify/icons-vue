<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh5mexb5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eh5mexb5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:api-blueprint" /></template>
