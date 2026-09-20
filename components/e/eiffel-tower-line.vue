<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbsmy68vk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbsmy68vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:eiffel-tower-line" /></template>
