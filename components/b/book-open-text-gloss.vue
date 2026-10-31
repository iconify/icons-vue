<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd-u4ybzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd-u4ybzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:book-open-text-gloss" /></template>
