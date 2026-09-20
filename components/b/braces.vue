<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4i8rebks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4i8rebks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:braces" /></template>
