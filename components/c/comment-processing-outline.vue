<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh-p1r4cs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wh-p1r4cs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:comment-processing-outline" /></template>
