<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itmyjfbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itmyjfbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fat-arrow-up-right" /></template>
