<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxxw5db8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxxw5db8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-line-style" /></template>
