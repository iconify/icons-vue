<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf4xfdbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hf4xfdbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:book-check-solid" /></template>
