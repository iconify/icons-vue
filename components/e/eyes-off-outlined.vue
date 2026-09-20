<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7m9o8f6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7m9o8f6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:eyes-off-outlined" /></template>
