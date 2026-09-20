<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukq-8fbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukq-8fbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:airbnb-fill" /></template>
