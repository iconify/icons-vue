<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg6j7hbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jg6j7hbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-line-line" /></template>
