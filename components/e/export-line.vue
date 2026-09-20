<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av8tbab7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="av8tbab7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:export-line" /></template>
