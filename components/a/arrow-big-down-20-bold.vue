<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eede2abzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eede2abzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-big-down-20-bold" /></template>
