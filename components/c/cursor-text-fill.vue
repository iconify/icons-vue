<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi916br-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi916br-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cursor-text-fill" /></template>
