<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2d2mobiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k2d2mobiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:csv" /></template>
