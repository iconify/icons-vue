<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixj357rxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ixj357rxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:dot" /></template>
