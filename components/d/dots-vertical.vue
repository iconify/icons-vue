<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn5adcdwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn5adcdwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dots-vertical" /></template>
