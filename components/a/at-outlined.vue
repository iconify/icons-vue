<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j355qtbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j355qtbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:at-outlined" /></template>
