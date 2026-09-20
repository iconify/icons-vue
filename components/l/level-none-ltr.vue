<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0ylx01sh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o0ylx01sh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:level-none-ltr" /></template>
