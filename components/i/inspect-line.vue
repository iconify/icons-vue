<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydruqtj8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydruqtj8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:inspect-line" /></template>
