<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5o27lvyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5o27lvyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:analytics" /></template>
