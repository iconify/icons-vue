<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwtb6jfzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwtb6jfzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:expand-right-line" /></template>
