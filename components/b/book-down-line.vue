<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwv08bcis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwv08bcis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-down-line" /></template>
