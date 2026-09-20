<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hump41b1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hump41b1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:add-line" /></template>
