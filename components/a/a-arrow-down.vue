<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-o_3jm7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-o_3jm7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:a-arrow-down" /></template>
