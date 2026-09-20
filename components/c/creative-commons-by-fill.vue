<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb0tbwbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb0tbwbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:creative-commons-by-fill" /></template>
