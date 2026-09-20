<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb-s0g_vo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bb-s0g_vo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:delete-2-line" /></template>
