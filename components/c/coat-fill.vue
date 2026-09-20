<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6rqg99ca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d6rqg99ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:coat-fill" /></template>
