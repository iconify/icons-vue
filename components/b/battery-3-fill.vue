<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhy-46b0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhy-46b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:battery-3-fill" /></template>
