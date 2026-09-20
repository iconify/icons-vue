<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yatbnbygi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yatbnbygi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-favorite" /></template>
