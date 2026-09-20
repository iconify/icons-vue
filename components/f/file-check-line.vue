<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oagmxbsks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oagmxbsks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-check-line" /></template>
