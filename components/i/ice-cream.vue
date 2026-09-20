<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxtd5ob1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jxtd5ob1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:ice-cream" /></template>
