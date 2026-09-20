<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iztd4sbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iztd4sbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:logout-1-remix" /></template>
