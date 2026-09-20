<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udvx3qmvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udvx3qmvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:funnel-plus" /></template>
