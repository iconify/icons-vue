<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onb2t3bho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onb2t3bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:attachment-2" /></template>
