<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw25tvi6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tw25tvi6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cloud-snow-fill" /></template>
