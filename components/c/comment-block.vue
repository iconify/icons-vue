<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc7udhbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc7udhbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-block" /></template>
