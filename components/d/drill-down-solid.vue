<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xufu5kyfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xufu5kyfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:drill-down-solid" /></template>
