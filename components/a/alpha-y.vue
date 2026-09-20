<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db9x-x-wx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="db9x-x-wx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-y" /></template>
