<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgu29hljj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lgu29hljj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:gitlab" /></template>
