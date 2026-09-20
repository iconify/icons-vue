<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvtrknbrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvtrknbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:copy-outlined" /></template>
