<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmm6urb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rmm6urb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:folder-placeholder-ltr" /></template>
