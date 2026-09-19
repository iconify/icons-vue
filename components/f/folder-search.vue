<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erd8cq3wx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erd8cq3wx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:folder-search" /></template>
