<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8cuki8wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x8cuki8wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:ice-cream-2" /></template>
