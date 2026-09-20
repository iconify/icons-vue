<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt-qhfbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt-qhfbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-up-left-waves-solid" /></template>
