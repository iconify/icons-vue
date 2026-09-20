<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-cyhzb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-cyhzb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-line-height" /></template>
