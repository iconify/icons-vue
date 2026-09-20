<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-p6c476e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-p6c476e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-bottom-line" /></template>
