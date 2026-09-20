<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm1lufbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="lm1lufbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:auto-flash" /></template>
