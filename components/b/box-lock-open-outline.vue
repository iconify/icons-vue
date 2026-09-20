<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn66o2gqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cn66o2gqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:box-lock-open-outline" /></template>
