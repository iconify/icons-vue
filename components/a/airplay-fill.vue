<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwoa4qbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwoa4qbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:airplay-fill" /></template>
