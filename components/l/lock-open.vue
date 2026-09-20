<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmd_9kbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmd_9kbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:lock-open" /></template>
