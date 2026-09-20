<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4sok7wcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4sok7wcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:edge-fill" /></template>
