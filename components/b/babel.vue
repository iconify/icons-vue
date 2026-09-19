<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz00n171p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iz00n171p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:babel" /></template>
