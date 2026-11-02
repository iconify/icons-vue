<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu-zd195g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu-zd195g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-heart-fill" /></template>
