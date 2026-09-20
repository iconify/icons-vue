<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3i5eof-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3i5eof-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cookie-man-filled" /></template>
