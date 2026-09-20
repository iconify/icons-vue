<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs-twgpig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs-twgpig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-strikethrough" /></template>
