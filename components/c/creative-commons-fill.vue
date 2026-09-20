<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npngynb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npngynb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:creative-commons-fill" /></template>
