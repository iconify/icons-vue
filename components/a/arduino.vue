<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7m6y0neb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t7m6y0neb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:arduino" /></template>
