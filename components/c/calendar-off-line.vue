<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6alyac8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6alyac8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-off-line" /></template>
