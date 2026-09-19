<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9b_vk3fy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="x9b_vk3fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:duplicate-small" /></template>
