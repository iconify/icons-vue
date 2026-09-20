<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hewnh0kei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hewnh0kei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-down-right" /></template>
