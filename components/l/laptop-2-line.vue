<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dad1ecbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dad1ecbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:laptop-2-line" /></template>
