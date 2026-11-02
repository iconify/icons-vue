<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqmgsn7hu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqmgsn7hu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chevrons-left-right-ellipsis-line" /></template>
