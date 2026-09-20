<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtpfbmb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dtpfbmb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:deer-head-under-paragraph" /></template>
