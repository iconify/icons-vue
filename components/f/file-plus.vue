<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw8zgtami.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nw8zgtami"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:file-plus" /></template>
