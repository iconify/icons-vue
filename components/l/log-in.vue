<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzu7m7bqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzu7m7bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:log-in" /></template>
