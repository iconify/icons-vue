<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq7hzcu1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq7hzcu1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:diamond-square-line" /></template>
