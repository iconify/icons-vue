<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4y2-lm7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4y2-lm7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:lottiefiles" /></template>
