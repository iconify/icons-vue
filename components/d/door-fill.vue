<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v22l6jbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v22l6jbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:door-fill" /></template>
