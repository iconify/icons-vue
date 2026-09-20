<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr6bf0bqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr6bf0bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:ar" /></template>
