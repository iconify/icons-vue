<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l00kb8f8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l00kb8f8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:clipboard-pulse" /></template>
