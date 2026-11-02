<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu-9zjbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu-9zjbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:happy-fill" /></template>
