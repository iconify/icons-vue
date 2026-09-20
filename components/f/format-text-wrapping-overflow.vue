<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6ckcpbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6ckcpbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-text-wrapping-overflow" /></template>
