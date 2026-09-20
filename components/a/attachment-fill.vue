<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybkd74bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybkd74bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:attachment-fill" /></template>
