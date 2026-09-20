<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep5h712et.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ep5h712et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:beer-bottles-row" /></template>
