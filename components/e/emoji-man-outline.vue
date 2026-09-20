<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sussbubbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sussbubbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoji-man-outline" /></template>
