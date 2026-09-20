<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld05h-xwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld05h-xwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:inbox-archive-line" /></template>
