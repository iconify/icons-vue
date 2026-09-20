<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wia3r3wym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wia3r3wym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:book-3-line" /></template>
