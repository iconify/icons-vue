<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv-oe6gwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv-oe6gwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-right-square-solid" /></template>
