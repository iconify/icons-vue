<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv7m9pbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uv7m9pbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:discussion-remove" /></template>
