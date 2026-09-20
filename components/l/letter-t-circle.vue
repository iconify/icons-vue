<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1jeizbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1jeizbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-t-circle" /></template>
