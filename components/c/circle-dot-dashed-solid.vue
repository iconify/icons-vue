<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtm5gdvwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtm5gdvwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-dot-dashed-solid" /></template>
