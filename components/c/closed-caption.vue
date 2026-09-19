<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4m5ftbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="u4m5ftbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:closed-caption" /></template>
