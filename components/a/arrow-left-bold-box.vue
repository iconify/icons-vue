<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef296zfzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef296zfzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-left-bold-box" /></template>
