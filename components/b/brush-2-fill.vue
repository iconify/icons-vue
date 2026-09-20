<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4boyfb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4boyfb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:brush-2-fill" /></template>
