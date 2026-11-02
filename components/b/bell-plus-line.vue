<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn145___z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn145___z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bell-plus-line" /></template>
